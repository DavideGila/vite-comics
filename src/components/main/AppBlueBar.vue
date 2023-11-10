<template>
    <div class="container d-flex justify-content-between align-items-center p-3">
        <div v-for="el in blueBar">
            <img :src="el.img" alt="">
            <span class="p-2 text-uppercase">{{ el.text }}</span>       
        </div>
    </div>
    
</template>

<script>
    export default {
        nome: 'AppBlueBar',
        data() {
            return {
                blueBar: [
                    {
                        img: '/img/buy-comics-digital-comics.png',
                        text: 'Digital Comics'
                    },
                    {
                        img: '/img/buy-comics-merchandise.png',
                        text: 'DC Merchandise'
                    },
                    {
                        img: '/img/buy-comics-subscriptions.png',
                        text: 'Subscription'
                    },
                    {
                        img: '/img/buy-comics-shop-locator.png',
                        text: 'Comic Shop Locator'
                    },
                    {
                        img: '/img/buy-dc-power-visa.svg',
                        text: 'DC Power Visa'
                    }                    
                ]
            }
        },
        
    }
</script>

<style lang="scss" scoped>
    span {
        color: white;
    }

    img {
        width: 40px;
    }
</style>