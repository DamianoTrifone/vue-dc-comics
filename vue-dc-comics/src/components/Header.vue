<template>
<div>
    <div class="container">
        <div class="header">
            <img src="../assets/dc-logo.png" alt="Logo DC">

                <ul>
                    <li v-for="link,index in links" :key="index">
                        <a class="link_header" :href="link">{{link.text}}</a>
                    </li>
                </ul>
        </div>       
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
    .header{
        margin-bottom: 50px;
    }
    img {
        width: 75px;
        margin-top: 20px;
        float: left;
        margin-right: 20px;
        // margin-left: 300px;
    } 
    li{
        display: inline-block;
        margin-top: 50px;
        margin-right: 60px;
    }
    .link_header{
        text-decoration: none;
        text-transform: uppercase;
        color: #303030;
        font-family: 'Roboto', sans-serif;
        font-size: 12px;
        padding-bottom: 50px;
        &:hover{
            color: #0282F9;
            text-decoration: underline;
        }
    }
</style>