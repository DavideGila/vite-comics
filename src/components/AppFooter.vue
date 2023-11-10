<template>
    <div class="bg-main">
        <div class="container d-flex">
            <div class="py-4 pe-3">
                <h4>DC COMICS</h4>
                <ul class="p-0">
                    <li v-for="element in first"><a href="">{{ element }}</a></li>
                </ul>
                <h4>SHOP</h4>
                <ul class="p-0">
                    <li v-for="element in second"><a href="">{{ element }}</a></li>
                </ul>
            </div>
            <div class="py-4 pe-3">
                <h4>DC</h4>
                <ul class="p-0">
                    <li v-for="element in third"><a href="">{{ element }}</a></li>
                </ul>
            </div>
            <div class="py-4 pe-3">
                <h4>SITES</h4>
                <ul class="p-0">
                    <li v-for="element in fourth"><a href="">{{ element }}</a></li>
                </ul>
            </div>
            <div class="bg-main-logo"></div>
        </div>
    </div>
    <div class="bg-grey py-4">
        <div class="container d-flex justify-content-between align-items-center p-0">
            <div>
                <button class="btn btn-primary">SIGN-UP NOW</button>
            </div>
            <div class="d-flex">
                <h4 class="pe-4">FOLLOW US</h4>
                <img src="/img/footer-facebook.png" alt="" class="pe-4">
                <img src="/img/footer-twitter.png" alt="" class="pe-4">
                <img src="/img/footer-youtube.png" alt="" class="pe-4">
                <img src="/img/footer-pinterest.png" alt="" class="pe-4">
                <img src="/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        nome: 'AppFooter',
        data() {
            return {
                first: [
                    'Characters',
                    'Comics',
                    'Movies',
                    'Tv',
                    'Games',
                    'Videos',
                    'News'
                ],
                second: [
                    'Shop DC',
                    'Shop DC Collectibles'
                ],
                third: [
                    'Terms of Use',
                    'Privacy Policy (New)',
                    'Ad Choices',
                    'Advertising',
                    'Jobs',
                    'Subscriptions',
                    'Talent Workshops',
                    'CPSC Certificates',
                    'Ratings',
                    'Shop Help',
                    'Contact Us'
                ],
                fourth: [
                    'DC',
                    'MAD Magazine',
                    'DC Kids',
                    'DC Universe',
                    'DC Power Visa',
                ]
            }
        },
    
    }
</script>

<style lang="scss" scoped>
a {
        text-decoration: none;
        color: grey;
    }
    li {
        list-style: none;
    }
    h4{
        color: white;
    }
    .bg-main {
        background-image: url('img/footer-bg.jpg');
        background-size: cover;
    }
    .bg-main-logo {
        background-image: url('/img/dc-logo-bg.png');
        background-position: right;
        background-repeat: no-repeat;
        width: 100%;
    }
    .bg-grey {
        background-color: rgb(53, 53, 53)
    }
</style>