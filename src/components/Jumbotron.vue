
<template>
    <section>
        <div class="jumbotron">
            <img src="../assets/img/jumbotron.jpg" alt="">
        </div>
        <div class="comics">
            <div class="container">
                <div class="title">
                    <h3>Current series</h3>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'Jumbotron'
}
</script>
<style scoped>
.jumbotron {
    height: 450px;
    overflow: hidden;
}
.jumbotron img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
}
.title {
    text-transform: uppercase;
    background-color: #097ceb;
    display: inline-block;
    padding: 8px;
    color: white;
    position: relative;
    left: 0;
    top: -19px;
}
</style>