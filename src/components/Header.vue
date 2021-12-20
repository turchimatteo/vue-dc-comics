<template>
    <header>
        <div class="first-header"></div>
        <div class="second-header">
            <div class="container">
                <nav>
                    <div class="logo">
                        <img src="../assets/img/dc-logo.png" alt="Logo DC">
                    </div>
                    <ul class="menu">
                        <li v-for="(link, index) in links" :key="index" :class="{ current: link.current }">
                            <a :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>
<style scoped>
.first-header {
    width: 100%;
    height: 70px;
    background-color: rgba(0, 0, 0, 0.849);
}
.second-header {
    width: 100%;
    padding: 20px;
    height: 120px;
    display: inline-block;
}
.container {
    width: 70%;
    display: flex;
    justify-content: center;
}
.menu {
    display: flex;
    list-style-type: none;
    justify-content: flex-end;
    
}
</style>

<script>
export default {
    name: "Header",
    data: function() {
        return {
            links: [
                {
                    text: 'CHARACTERS',
                    url: '#',
                    current: false
                },
                {
                    text: 'COMICS',
                    url: '#',
                    current: true
                },
                {
                    text: 'MOVIES',
                    url: '#',
                    current: false
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false
                },
                {
                    text: 'GAMES',
                    url: '#',
                    current: false
                },{
                    text: 'COLLECTIBLES',
                    url: '#',
                    current: false
                },{
                    text: 'VIDEOS',
                    url: '#',
                    current: false
                },{
                    text: 'FANS',
                    url: '#',
                    current: false
                },{
                    text: 'NEWS',
                    url: '#',
                    current: false
                },{
                    text: 'SHOP',
                    url: '#',
                    current: false
                },
            ],
        };
    }
}
</script>