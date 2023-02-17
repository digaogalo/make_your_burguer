<template>
    <div id="main-banner">
        <h1>Pizza Bellissimo</h1>
    </div>
</template>

<script>

export default {
    name: 'Banner',
}
</script>

<style scoped>
    #main-banner {
        background-image: url('../../public/img/pizza.jpg');
        background-size: cover;
        height: 700px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: transparent;
        padding: 20px 40px;
    }
</style>


