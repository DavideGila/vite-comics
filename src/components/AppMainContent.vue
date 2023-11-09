<template>
    <div class="bg-dark">
        <div class="container">
            <h1 class="m-0"><a href="">Content</a></h1>
        </div>   
    </div>
    <div class="bg-primary d-flex">
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