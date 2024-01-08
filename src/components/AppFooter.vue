<script>
export default {
    
}
</script>
<template lang="">
    <div class="blu-list">
        <div class="container">

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
        height: 100px;
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