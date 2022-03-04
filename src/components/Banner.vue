<template>
    <div id="main-banner" :style="image">
        <h1>Maker Your Burgyuer</h1>
    </div>
</template>

<script>
export default {
    name: 'Banner',
    data() {
        return {
            image: {backgroundImage: "url(img/burger.jpg)"}
        }
    }
}
</script>

<style scoped>

    #main-banner {
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>