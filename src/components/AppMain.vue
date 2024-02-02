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
            <h2>Current Series</h2>
            <div class="container card-container">
                <ComicCard />
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
#comics {
    background-color: #1C1C1C;
    padding: 50px 15px;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 30px;

    .comic-card {
        flex-basis: calc(100% / 6);
    }
}
</style>