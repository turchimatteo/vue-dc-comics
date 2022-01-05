<template>
    <div class="comic-container">
        <img :src="element.thumb" :alt="element.series">
        <div class="title">
            {{ element.series.toUpperCase() }}
        </div>
    </div>
</template>
<script>
export default {
    name: 'Comic',
    props: ['element'],
}
</script>
<style scoped>
.comic-container {
    width: calc(100% / 7);
    margin: 10px;
    background-color: #0e0e0e;
}
.title {
    color: white;
}
</style>