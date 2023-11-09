<template>
    <template v-for="item in componentList">
        <div v-html="item.content"></div>
    </template>
</template>

<script setup lang="ts">
    import {Component} from "../defs/types";
    defineProps<{ componentList: Component[] }>()
</script>
