<template>
    <div id="app">
        <div id="nav">
            </div>
        <router-view />
    </div>
</template>

<script>
// import Login from './components/Login';
    export default {
        name: 'App'
    }
        
</script>

<style>
    body {
        background-color: #F0F0F0;
    }
    h1 {
        padding: 0;
        margin-top: 0;
    }
    #app {
        width: 100vw;
        margin: auto;
        height: 100vh;
    display: flex;
    }
</style>