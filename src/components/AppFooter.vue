<script>
import AppFooterTop from './AppFooterTop.vue';
import AppFooterBottom from './AppFooterBottom.vue';

export default {
    name: 'AppFooter',
    components: { AppFooterTop, AppFooterBottom }
};
</script>

<template>
    <footer>
        <AppFooterTop />
        <AppFooterBottom />
    </footer>
</template>

<style></style>