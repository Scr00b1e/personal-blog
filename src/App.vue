<template>
    <Header></Header>
    <h1>hey</h1>
</template>

<script lang="ts">
import Header from './components/Header.vue'
export default {
    components: {
        Header
    }
}
</script>

<style lang="scss">
@tailwind base;
@tailwind components;
@tailwind utilities;

*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
</style>
