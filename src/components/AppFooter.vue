<template>
    <div>
        <div class="container d-flex">
            <div>
                <h4>DC COMICS</h4>
                <ul class="p-0">
                    <li v-for="element in first"><a href="">{{ element }}</a></li>
                </ul>
                <h4>SHOP</h4>
                <ul class="p-0">
                    <li v-for="element in second"><a href="">{{ element }}</a></li>
                </ul>
            </div>
            <div class="ps-3">
                <h4>DC</h4>
                <ul class="p-0">
                    <li v-for="element in third"><a href="">{{ element }}</a></li>
                </ul>
            </div>
            <div class="ps-3">
                <h4>SITES</h4>
                <ul class="p-0">
                    <li v-for="element in fourth"><a href="">{{ element }}</a></li>
                </ul>
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
        color: white;
    }
    li {
        list-style: none;
    }
    h4{
        color: white;
    }
    .bg-main {
        background-image: url('img/')
    }
</style>