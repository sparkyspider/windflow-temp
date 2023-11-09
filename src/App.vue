<template>
    <div class="flex flex-row h-screen items-center justify-center">
        <div class="flex flex-col">
            <div><img :src="windflowLogo" class="w-64"></div>
            <div class="flex flex-row justify-center mt-2 mb-8 text-sm">
                <span class="font-light text-gray-400">app innovation with&nbsp;</span><span class="text-gray-300">Mark van Wyk</span>
            </div>
            <div class="flex justify-center">
                <button class="flex flex-row text-white bg-gradient-to-b from-blue-700 to-blue-900 border-neutral-900 border-2 rounded-xl p-0.5 items-center justify-center drop-shadow-md" @click="go">
                    <div class="fill-current font-black pl-2 text-xl">
                            in
                    </div>
                    <div class="flex ml-1 text-sm h-full rounded-sm items-center p-1 pr-2">
                        <span class="font-light text-gray-300">Connect on&nbsp;</span><span class="font-semibold text-gray-100">LinkedIn</span>
                    </div>
                </button>
            </div>
        </div>
    </div>
</template>
<script setup lang="ts">
    import windflowLogo from '../src/assets/windflow-logo.svg'

    function go() {
        window.location.href = 'https://www.linkedin.com/in/markvwyk/'
    }
</script>