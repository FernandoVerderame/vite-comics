<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'CHARACTERS',
                url: '#',
                active: false
            },
            {
                text: 'COMICS',
                url: '#',
                active: true
            },
            {
                text: 'MOVIES',
                url: '#',
                active: false
            },
            {
                text: 'TV',
                url: '#',
                active: false
            },
            {
                text: 'GAMES',
                url: '#',
                active: false
            },
            {
                text: 'COLLECTIBLES',
                url: '#',
                active: false
            },
            {
                text: 'VIDEOS',
                url: '#',
                active: false
            },
            {
                text: 'FANS',
                url: '#',
                active: false
            },
            {
                text: 'NEWS',
                url: '#',
                active: false
            },
            {
                text: 'SHOP',
                url: '#',
                active: false
            }
        ]
    })
};
</script>

<template>
    <header>
        <nav class="container">
            <div class="navbar-logo">
                <img src="../../src/assets/img/dc-logo.png" alt="logo-header">
            </div>
            <div class="navbar-links">
                <ul>
                    <li v-for="(link, i) in links" :key="i">
                        <a :href="link.url" :class="{ active: link.active }">{{ link.text }}</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<style>
header {
    background-color: goldenrod;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar-logo img {
    height: 80px;
}

.navbar-logo {
    padding: 20px 0;
}

.navbar-links ul {
    display: flex;
}

.navbar-links a {
    color: black;
    font-size: 12px;
    font-weight: 600;
    padding: 15px 12px;
}

.navbar-links a:hover {
    background-color: #0282F9;
    transition: .4s;
}

.navbar-links a.active {
    color: #0282F9;
}
</style>