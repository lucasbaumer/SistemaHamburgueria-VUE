<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>
</template>

<script>
    export default{
        name: "Banner",

    }
</script>

<style scoped>
    #main-banner{
        background-image: url('C:\Users\Lyncas\Documents\vueCurso\projetoFinal\public\img\burger.jpg');
        background-position: 0 -260px;
        background-size: cover;
        height: 840px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        color: #FFF;
        text-align: center;
        font-size: 80px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>