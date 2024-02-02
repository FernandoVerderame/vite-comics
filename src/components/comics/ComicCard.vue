<script>
export default {
    name: 'ComicCard',
    props: {
        thumb: String,
        series: String
    }
};
</script>

<template>
    <div class="comic-card">
        <div class="thumb">
            <img :src="thumb" :alt="series">
        </div>
        <h3>{{ series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
.comic-card {

    h3 {
        font-size: 12px;
        margin: 15px 0;
        color: white;
        text-transform: uppercase;
    }
}

.thumb {
    width: 180px;
    height: 180px;

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: center top;
    }
}
</style>