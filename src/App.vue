<template>
    <Header />
    <div class="w-full max-w-6xl mt-0 mx-auto">
        <div class="flex justify-between mt-5">
            <Main />
            <Sidebar />
        </div>
    </div>
</template>

<script lang="ts">
import Main from './components/Main.vue'
import Sidebar from './components/Sidebar.vue'
import Header from './components/Header.vue'
import './main.scss'
export default {
    components: {
        Main,
        Sidebar,
        Header
    }
}
</script>

<style lang="scss"></style>