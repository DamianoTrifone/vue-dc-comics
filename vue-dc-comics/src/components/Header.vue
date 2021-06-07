<template>
<div>
    <img src="../assets/dc-logo.png" alt="Logo DC">
    <li>
        <a href="">Characters</a>
        <a href="">Comics</a>
        <a href="">Movies</a>
        <a href="">Tv</a>
        <a href="">Games</a>
        <a href="">Collectibles</a>
        <a href="">Videos</a>
        <a href="">Fans</a>
        <a href="">News</a>
        <a href="">Shop</a>
    </li>
</div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss">
    *{
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap');
    }
    img {
        width: 75px;
        margin-top: 20px;
        margin-left: 300px;
    } 
    li{
        display: inline-block;
        float: right;
        margin-top: 50px;
        margin-right: 60px;
    }
    a{
        padding: 15px;
        text-decoration: none;
        text-transform: uppercase;
        color: #303030;
        font-family: 'Roboto', sans-serif;

        &:hover{
            color: #0282F9;
            text-decoration: underline;
        }
    }
</style>