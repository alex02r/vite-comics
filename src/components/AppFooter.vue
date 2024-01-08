<script>
export default {
    
}
</script>
<template lang="">
    <div class="blu-list">
        <div class="container">
            <div class="list">
                <ul>
                    <li>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="comics">
                        DIGITAL COMICS
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="comics">
                        DC MERCHANDISE
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="comics">
                        SUBSCRIPTIO
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="comics">
                        COMIC SHOP LOCATOR
                    </li>
                    <li>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="comics">
                        DC POWER VISA
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <footer>
        <div class="container">
            <div class="content-footer">
                <div class="side-footer">

                </div>
                <div class="side-footer logo-dc">
                </div>
            </div>
        </div>
        <div class="bottom-footer">
            <div class="container">
                <div class="content-footer">
                    <div class="side-footer">
    
                    </div>
                    <div class="side-footer">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
    .container{
        max-width: 1200px;
        margin: 0 auto;
    }
    .blu-list{
        background-color: rgb(15, 159, 255);
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
                    color: #fff;
                    img{
                        max-width: 50px;
                        height: 50px;
                    }
                    font-size: 14px;
                }
            }
        }
    }
    footer{
        background-image: url('../assets/img/footer-bg.jpg');
        .content-footer{
            display: flex;
            justify-content: space-between;
            .side-footer{
                width: 500px;
                height: 400px;
                background-color: #fff;
            }
            .logo-dc{
                background-image: url('../assets/img/dc-logo-bg.png');
            }
        }
        .bottom-footer{
            background-color: black;
            height: 100px;
        }

    }

</style>