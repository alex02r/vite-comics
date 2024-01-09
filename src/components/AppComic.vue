<script>
export default {
    props:{
        comic_obj: Object
    }
}
</script>
<template lang="">
    <div class="comic">
        <img :src="comic_obj.thumb" :alt="comic_obj.series">
        <h3>{{ comic_obj.series }}</h3>
    </div>
</template>
<style lang="scss" scoped>
    .comic{
        width: calc(100% / 6 - 20px);
        img{
            width: 100%;
            max-height: 200px;
        }
    }
</style>