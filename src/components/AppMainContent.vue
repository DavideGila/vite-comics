<template>
    <div class="bg-dark">
        <div class="container">
            <h1 class="m-0 text-white">Content</h1>
        </div>   
    </div>
    <div class="bg-primary d-flex py-4">
        <AppBlueBar />
    </div>    
</template>

<script>
    import AppBlueBar from './main/AppBlueBar.vue'

    export default {
        nome: 'AppMainContent',
        components: {
            AppBlueBar
        },
    }
</script>

<style lang="scss" scoped>
    a {
        text-decoration: none;
    }
</style>