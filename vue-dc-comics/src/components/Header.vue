<template>
<div>
    <div class="container">
        <img src="../assets/dc-logo.png" alt="Logo DC">

            <ul>
                <li v-for="link,index in links" :key="index">
                    <a :href="link">{{link.text}}</a>
                </li>
            </ul>
    </div>
</div>
</template>

<script>
export default {
    name: "Header",
    data () {
        return {
            links: [
                {
                    text: "characters",
                    active: false
                },
                {
                    text: "comics",
                    active: true
                },
                {
                    text: "movies",
                    active: false
                },
                {
                    text: "tv",
                    active: false
                },
                {
                    text: "games",
                    active: false
                },
                {
                    text: "collectibles",
                    active: false
                },
                {
                    text: "videos",
                    active: false
                },
                {
                    text: "fans",
                    active: false
                },
                {
                    text: "new",
                    active: false
                },
                {
                    text: "shop",
                    active: false
                },
            ]
        }
    }
    }
</script>

<style lang="scss"> 
    img {
        width: 75px;
        margin-top: 20px;
        // margin-left: 300px;
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