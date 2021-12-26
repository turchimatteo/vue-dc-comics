<template>
    <footer>
        <div class="container">
            <div class="wrapper">
                <div class="iscriviti">
                    <span>Sign-Up Now!</span>
                </div>
                <div class="socials">
                    Follow us
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>
<style scoped>
footer {
    background-color: rgba(0, 0, 0, 0.849);
    z-index: 1;
    text-transform: uppercase;
}
.wrapper {
    height: 120px;
    display: flex;
    justify-content: space-between;
    align-content: center;
}
.iscriviti {
    margin-top: 50px;
}
span {
    color: white;
    border: 2px solid blue;
    padding: 10px;
}
.socials {
    color: blue;
    display: flex;
    align-items: center;
    font-weight: bold;
    font-size: 20px;
}
img {
    margin-left: 10px;
}
</style>