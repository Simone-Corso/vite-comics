<template lang="">
    <footer>
       <div class="container-img">
       <ul>
        <h2>
            DC COMICS
        </h2>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
       </ul>

       <ul>
        <h2>
            SHOP
        </h2>
        <li>Shop DC</li>
        <li>Shop DC collectibles</li>
       </ul>

       <ul>
        <h2>
            DC
        </h2>
        <li>Terms Of Use</li>
        <li>Privacy policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertsing</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
       </ul>

       <ul>
        <h2>
            SITES
        </h2>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>  
    </ul>
       </div>
    </footer>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>

.container-img{
    width: 100%;
    height: 450px;
    background-image: url(../assets/img/footer-bg.jpg);
    display: flex;
    align-items: center;
    flex-direction: column;
    flex-wrap: wrap;
    align-content: flex-start;

}

img{
    width: 100%;
    height: 450px;
}

ul{
    color: #797979;
    list-style-type: none;
}

h2{
    color: white;
    font-size: 20px;
}

    
</style>