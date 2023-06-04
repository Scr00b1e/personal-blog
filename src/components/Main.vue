<template>
    <div class="main w-full bg-slate-400 p-3 mr-3">
        <h1>main</h1>
        <post-item></post-item>
        <post-item></post-item>
        <post-item></post-item>
    </div>
</template>

<script lang="ts">
import PostItem from './PostItem.vue';
export default {
    components: {
        PostItem
    }
}
</script>

<style lang="scss" scoped></style>