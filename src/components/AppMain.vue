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
        <div class="container">
            <div class="main-contect">-- Content goes here --</div>
        </div>
    </main>
</template>

<style>
main {
    background-color: #1C1C1C;

}

.main-contect {
    font-size: 30px;
    color: white;
    padding: 40px 0;
}
</style>