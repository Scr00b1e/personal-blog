<template>
    <div class="sidebar bg-slate-300 h-3/5 w-full pb-3 ml-3">
        <div class="text-center">
            <ul>
                <li class="tags__item">Thoughts</li>
                <li class="tags__item">Stuff</li>
                <li class="tags__item">Stuff</li>
                <li class="tags__item">Stuff</li>
                <li class="tags__item">Stuff</li>
            </ul>
        </div>
        <div class="p-3">
            <p class="mb-3">Checkout my portfolio</p>
            <img src="" alt="" class="w-full h-5">
        </div>
    </div>
</template>

<script lang="ts">
export default {

}
</script>

<style lang="scss" scoped>
.tags__item {
    width: 100%;
    padding: 10px 0;
    background: rgba(#324c6f, .7);
    font-weight: 500;

    &:hover {
        background: rgba(#324c6f, .6);
    }
}
</style>