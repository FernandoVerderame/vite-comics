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
        <img :src="thumb" :alt="series">
        <h3>{{ series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
.comic-card {
    padding: 15px;
    background-color: #1C1C1C;

    h3 {
        font-size: 12px;
        margin: 15px 0;
        color: white;
        text-transform: uppercase;
    }
}
</style>