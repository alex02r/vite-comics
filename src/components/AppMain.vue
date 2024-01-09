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
            ],
            comics:[
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book",
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book",
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel",
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book",
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel",
                },
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