<script>
import AppHeader from './components/AppHeader.vue';

export default {
    name: 'Vite DC Comics',

    components: { AppHeader }
};
</script>

<template>
    <AppHeader />
</template>

<style>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Generics */
img {
    max-width: 100%;
    display: block;
}

ul {
    list-style-type: none;
}

a {
    text-decoration: none;
}

/* Utils */
.container {
    max-width: 1200px;
    margin: 0 auto;
}
</style>