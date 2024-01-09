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
@use '../styles/generals.scss';
@use '../styles/partials/variables' as *;
    .comic{
        width: calc(100% / 6 - 20px);
        img{
            width: 100%;
            max-height: 200px;
        }
        h3{
            color: $white;
        }
    }
</style>