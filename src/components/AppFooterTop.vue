<script>
export default {
    name: 'AppFooterTop'
};
</script>

<template>
    <div class="links">
        <div class="dc-comics-links">
            <h4>DC COMICS</h4>
            <ul>
                <li>
                    <a href="#">Characters</a>
                </li>
                <li>
                    <a href="#">Comics</a>
                </li>
                <li>
                    <a href="#">Movies</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">Games</a>
                </li>
                <li>
                    <a href="#">Videos</a>
                </li>
                <li>
                    <a href="#">News</a>
                </li>
            </ul>
        </div>
        <div class="shop-links">
            <h4>SHOP</h4>
            <ul>
                <li>
                    <a href="#">Shop DC</a>
                </li>
                <li>
                    <a href="#">Shop DC Collectibles</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="dc-links"></div>
    <div class="sites-links"></div>
</template>

<style>
h4 {
    font-size: 18px;
    margin-bottom: 10px;
}

ul li {
    padding: 4px 0;
}

ul li a {
    color: gray;
    font-size: 14px;
}

.dc-comics-links {
    margin-bottom: 20px;
}
</style>