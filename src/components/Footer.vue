<template>
    <footer>
        <div class="container">
            <div class="left-footer">
                <ul>
                    <li><h4>Dc comics</h4></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>

                    <li><h4>Shop</h4></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
                <ul>
                    <li><h4>Dc</h4></li>
                    <li><a href="#">Terms of use</a></li>
                    <li><a href="#">Privacy policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>
                    <li><h4>Sites</h4></li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Vista</a></li>
                </ul>
            </div>
            <div class="right-footer">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>
<style scoped>
footer {
    background-image: url('../assets/img/footer-bg.jpg');
    width: 100%;
    height: 400px;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    flex-direction: row;
    align-items: center;
}
.left-footer {
    width: 50%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    padding: 20px;
}
ul {
    list-style-type: none;
}
h4 {
    color: white;
    font-size: 20px;
    margin-bottom: 10px;
    margin-top: 10px;
    text-transform: uppercase;
}
a {
    color: grey;
    text-decoration: none;
}
.right-footer {
    width: 50%;
    float: right;
    /* da sistemare in maniera più corretta */
    position: relative;
    right: 0;
    bottom: 300px;
}
.right-footer img {
    width: 70%;
    z-index: 2;
}
</style>