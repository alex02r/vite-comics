<script>
export default {
    
}
</script>
<template lang="">
    <div class="container">
        <header>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div class="nav-list">
                <ul>
                    <li>CHARACTERS</li>
                    <li class="active">COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>
        </header>
    </div>
</template>
<style lang="scss" scoped>
@use '../styles/variables.scss' as *;
    .container{
        max-width: 1200px;
        margin: 0 auto;
        header{
            display: flex;
            justify-content: space-between;
            align-items: center;
            .logo img{
                width: 80px;
            }
            .nav-list{
                ul{
                    list-style: none;
                    display: flex;
                    li{
                        padding: 50px 0;
                        font-size: 14px;
                        margin: 0 10px;
                        font-weight: 600;
                        
                    }
                    li.active{
                        color: $primary;
                        border-bottom: 3px solid $primary;
                    }
                }
            }
        }
        
    }
    
</style>