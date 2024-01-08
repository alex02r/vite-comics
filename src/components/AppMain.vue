<script>
export default {
    data() {
        return {
            blue_lists:[
                {
                    img: '/src/assets/img/buy-comics-digital-comics.png',
                    title: 'DIGITAL COMICS'
                },
                {
                    img: '/src/assets/img/buy-comics-merchandise.png',
                    title: 'DC MERCHANDISE'
                },
                {
                    img: '/src/assets/img/buy-comics-subscriptions.png',
                    title: 'SUBSCRIPTION'
                },
                {
                    img: '/src/assets/img/buy-comics-shop-locator.png',
                    title: 'COMIC SHOP LOCATOR'
                },
                {
                    img: '/src/assets/img/buy-dc-power-visa.svg',
                    title: 'DC POWER VISA'
                }
            ]
        }
    },
}
</script>
<template lang="">
    <main>
        <div class="container">
            <h2> --> Content goes here <-- </h2>
        </div>
    </main>
    <div class="blu-list">
        <div class="container">
            <div class="list">
                <ul>
                    <li v-for="(item, index) in blue_lists" :key="index">
                        <img :src="item.img" :alt="item.title">
                        {{ item.title }}
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
@use '../styles/variables.scss' as *;
    .container{
        max-width: 1200px;
        margin: 0 auto;
    }
    main{
        background-color: black;
        h2{
        padding: 50px 0;
        color: white;
        }
    }
    .blu-list{
        background-color: $primary;
        width: 100%;
        .list{
            ul{
                display: flex;
                justify-content: center;
                align-items: center;
                list-style: none;
                li{
                    display: flex;
                    align-items: center;
                    gap: 10px;
                    margin: 40px 30px;
                    color: $white;
                    img{
                        max-width: 50px;
                        height: 50px;
                    }
                    font-size: 14px;
                }
            }
        }
    }
</style>