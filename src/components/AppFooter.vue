<script>
export default {
   
}
</script>
<template lang="">
    <footer>
        <div class="container">
            <div class="content-footer">
                <div class="lists-group">
                    <div class="footer-list">
                        <h4>DC COMICS</h4>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Collectibles</li>
                            <li>Videos</li>
                            <li>Fans</li>
                            <li>News</li>
                            <li>Shop</li>
                        </ul>
                        <h4>SHOP</h4>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <div class="footer-list">
                        <h4>DC</h4>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Collectibles</li>
                            <li>Videos</li>
                            <li>Fans</li>
                            <li>News</li>
                            <li>Shop</li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <div class="footer-list">
                        <h4>SITES</h4>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                        </ul>
                    </div>
                </div>
                <div class="logo-dc">
                </div>
            </div>
        </div>
        <div class="bottom-footer">
            <div class="container">
                <div class="content-footer">
                    <div>
                        <div class="btn">
                            SIGN-UP NOW!
                        </div>
                    </div>
                    <div class="side-footer">
                        <h4>FOLLOW US</h4>
                        <div class="icons">
                            <img src="../assets/img/footer-facebook.png" alt="facebook">
                            <img src="../assets/img/footer-twitter.png" alt="twitter">
                            <img src="../assets/img/footer-youtube.png" alt="youtube">
                            <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                            <img src="../assets/img/footer-periscope.png" alt="periscope">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style lang="scss" scoped>
@use '../styles/generals.scss';
@use '../styles/partials/variables' as *;
    .container{
        max-width: 1200px;
        margin: 0 auto;
    }
    footer{
        background-image: url('../assets/img/footer-bg.jpg');
        .content-footer{
            display: flex;
            justify-content: space-between;
            .lists-group{
                display: flex;
                padding: 30px 0;
                color: $white;
                ul{
                    margin: 10px 0;
                    list-style: none;
                    color: #717171;
                    font-size: 14px;
                }
            }
            .logo-dc{
                width: 600px;
                background-image: url('../assets/img/dc-logo-bg.png');
                background-size: cover;
            }
        }
        .bottom-footer{
            background-color: #303030;
            padding: 30px 0;
            .btn{
                padding: 10px;
                color: $white;
                border: 2px solid $primary;
            }
            .side-footer{
                display: flex;
                align-items: center;
                gap: 20px;
                color: $primary;
                .icons img{
                    margin: 0 5px;
                }
            }
        }

    }

</style>