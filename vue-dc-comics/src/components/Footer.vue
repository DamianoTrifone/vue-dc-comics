<template>
    <div class="principale">
        <div class="container">
            <div class="footer-content">
                <div class="">
                <h2>Dc comics</h2>
                <a class="link_footer" href="">Characters</a>
                <a class="link_footer" href="">Comics</a>
                <a class="link_footer" href="">Movies</a>
                <a class="link_footer" href="">TV</a>
                <a class="link_footer" href="">Games</a>
                <a class="link_footer" href="">Videos</a>
                <a class="link_footer" href="">News</a>

                <h2>SHOP</h2>
                <a class="link_footer" href="">Shop DC</a>
                <a class="link_footer" href="">Shop DC Collectibles</a>
            </div>
            <div>
                <h2>DC</h2>
                <a class="link_footer" href="">Terms of use</a>
                <a class="link_footer" href="">Privacy policy (new)</a>
                <a class="link_footer" href="">Ad choises</a>
                <a class="link_footer" href="">Advertising</a>
                <a class="link_footer" href="">Jobs</a>
                <a class="link_footer" href="">Subscriptions</a>
                <a class="link_footer" href="">Talent workshops</a>
                <a class="link_footer" href="">CPSC certificates</a>
                <a class="link_footer" href="">Ratings</a>
                <a class="link_footer" href="">shop help</a>
                <a class="link_footer" href="">Contact us</a>
            </div>
            <div>
                <h2>SITES</h2>
                <a href="" class="link_footer">DC</a>
                <a href="" class="link_footer">MAD Magazine</a>
                <a href="" class="link_footer">DC kids </a>
                <a href="" class="link_footer">DC universe</a>
                <a href="" class="link_footer">DC power visa</a>
            </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss">
    .principale{
        background-image: url(../assets/footer-bg.jpg);
        background-repeat: no-repeat;
    }
    .footer-content {
        display: flex;
    }
    h2{
        color: white;
        text-transform: uppercase;
        padding: 8px 0px;
    }
    .link_footer{
        color: lightslategray;
        display: block;
        font-size: 10px;
        text-transform: capitalize;
        padding: 4px;
    }
</style>