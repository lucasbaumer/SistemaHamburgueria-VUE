<template>
    <div>
    <div id="nav">
    <router-link to="/" id="logo-url">
        <img :src="logo" :alt="alt" id="logo">
    </router-link>
    <router-link to="/">Home</router-link> 
    <router-link to="/about">Pedidos</router-link> 
    </div>
    <router-view/>
    </div>
</template>

<script>
    export default{
        name: 'navBar',
        props: ['logo', 'alt'],
    }
</script>

<style scoped>
#nav{
    background-color: #222;
    border-bottom: 4xp solid #111;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

#nav #logo-url{
    margin: auto;
    margin-left: 0;
}

#logo{
    width: 40px;
    height: 40px;
}

#nav a{
    color: #fcba03;
    text-decoration: none;
    margin: 12px;
    transition: 0.5;
}

#nav a:hover{
    color: #FFF;
}
</style>