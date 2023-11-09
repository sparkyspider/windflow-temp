<template>
    <WindflowArea :componentList="componentList"></WindflowArea>
    <div class="mt"></div>
</template>
<script setup lang="ts">
import WindflowArea from "./WindflowArea.vue";
import {Component} from "../defs/types";

const componentList:Component[] = [
    {
        name: 'HeaderBar',
        content: '<div>Header Bar</div>'
    },
    {
        name: 'HeroImage',
        content: '<div>Hero Image</div>'
    }
]
</script>
