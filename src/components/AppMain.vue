<script>
import ComicCard from './comics/ComicCard.vue';

export default {
    name: 'AppMain',
    props: {
        comics: Array
    },

    components: { ComicCard, ComicCard }
};
</script>

<template>
    <main>
        <section id="comics">
            <div class="container">
                <h2>Current Series</h2>
                <div class="card-container">
                    <ComicCard v-for="(comic, i) in comics" :key="i" :thumb="comic.thumb" :series="comic.series" />
                </div>
            </div>
            <div class="lead-more">
                <div class="button">
                    <a href="#">Lead More</a>
                </div>
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
#comics {
    background-color: #1C1C1C;
    padding-top: 30px;
    position: relative;

    h2 {
        font-size: 20px;
        padding: 15px 0;
        color: white;
        text-align: center;
        width: 230px;
        text-transform: uppercase;
        background-color: #0282F9;
        position: absolute;
        top: -20px;
    }
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 30px;

    .comic-card {
        flex-basis: calc(100% / 6);
        padding: 10px;
    }
}

.lead-more {
    display: flex;
    justify-content: center;

    .button {
        margin: 40px 0;

        a {
            font-size: 15px;
            text-transform: uppercase;
            color: white;
            width: 200px;
            padding: 10px 50px;
            background-color: #0282F9;
        }
    }


}
</style>