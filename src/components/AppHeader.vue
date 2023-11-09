<template>
    <div class="d-flex justify-content-between align-items-center py-4">
        <img src="/img/dc-logo.png" alt="Logo-DC">
        <div>
        <ul class="d-flex">
            <li v-for="nav in navBar" class="pe-4"><a href="">{{ nav }}</a></li>
        </ul>
        </div>
    </div>   
</template>

<script>
    export default {
        nome: 'AppHeader',
        data() {
            return {
                navBar: [
                    'Characters',
                    'Comics',
                    'Movies',
                    'TV',
                    'Games',
                    'Collectibles',
                    'Videos',
                    'Fans',
                    'News',
                    'Shop'
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>
    li {
        list-style: none;
    }

    a {
        text-decoration: none;
        color: black;
    }
</style>