<script>
export default {
    name: 'AppHeader'
};
</script>

<template>
    <header>
        <nav class="container">
            <div class="navbar-logo">
                <img src="../../src/assets/img/dc-logo.png" alt="logo-header">
            </div>
            <div class="navbar-links"></div>
        </nav>
    </header>
</template>

<style>
header {
    background-color: goldenrod;
}

.navbar-logo img {
    height: 80px;
}

.navbar-logo {
    padding: 20px 0;
}
</style>