<script>
export default {
    name: 'AppFooterBottom'
};
</script>

<template>
    <div class="footer-bottom">
        <div class="buttons container">
            <div class="sign-up-button"><a href="#">SIGN-UP NOW!</a></div>
            <div class="social-buttons">
                <h3>FOLLOW US</h3>
                <ul>
                    <li>
                        <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-pinterest.png" alt="pintrest"></a>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style>
.footer-bottom {
    background-color: #303030;
    padding: 50px;

    .buttons {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}

.sign-up-button a {
    font-size: 18px;
    color: white;
    border: #0C7CEC 2px solid;
    padding: 15px;

    &:hover {
        background-color: #0C7CEC;
        transition: .4s;
    }
}

.social-buttons {
    display: flex;
    align-items: center;
    gap: 25px;

    ul {
        display: flex;
        gap: 20px;
    }
}
</style>