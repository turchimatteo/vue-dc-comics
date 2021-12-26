<template>
    <footer>
        <div class="icons">
            <div class="container-shop">
                <ul>
                    <li v-for="(element, index) in shop" :key="index">
                        <div class="logo"><img :src="element.logo" :alt="index"></div>
                        <span>{{ element.text }}</span>
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Icons",
    data: function(){
        return{
            shop: [
                {
                    logo: require("../assets/img/buy-comics-digital-comics.png"),
                    text: "DIGITAL COMICS",
                },
                {
                    logo: require("../assets/img/buy-comics-merchandise.png"),
                    text: "DC MERCHANDISE",
                },
                {
                    logo: require("../assets/img/buy-comics-subscriptions.png"),
                    text: "SUBSCRIPTION",
                },
                {
                    logo: require("../assets/img/buy-comics-shop-locator.png"),
                    text: "COMIC SHOP LOCATOR",
                },
                
            ],
        }
    }
}
</script>

<style scoped>
.icons{
    height: 150px;
    background: #0282f9;
    display: flex;
    align-items: center;  
    z-index: 1;   
}
ul{
    height: 100%;
    display: flex;
    list-style-type: none;
    justify-content: center;
    justify-content: space-between;        
}
li{
    display: flex;
    align-items: center;
    color: white;
    margin-left: 130px;            
}
.logo{
width: 50px;
margin-right: 10px;
}
</style>