<template>
    <div id="app" class="flex flex-col justify-center items-center w-screen h-screen bg-gray-900 text-white">
        <h1 class="text-6xl font-medium mb-8">Thomas Gredin</h1>
        <p class="text-xl font-medium">Construction en cours</p>
        <!-- <router-view/> -->
    </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class App extends Vue {}
</script>