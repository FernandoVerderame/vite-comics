<script>
export default {
    name: 'AppMain',
    props: {
        comics: Array
    }
};
</script>

<template>
    <main>
        <section id="comics">
            <h2>Current Series</h2>
            <div class="container card-container">

            </div>
        </section>
    </main>
</template>

<style>
#comics {
    background-color: #1C1C1C;
    padding: 50px 15px;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 30px;
}
</style>