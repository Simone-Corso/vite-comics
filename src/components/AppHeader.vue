<template lang="">

<header>
    <nav class="menu">
    <article>
            <ul>
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
            </ul>
        </article>
    </nav>

</header>
     
</template>
<script>

import AppMenu from './AppMenu.vue';

export default {
    name: 'AppHeader',
    components: {
        AppMenu,
    }
    
}
</script>
<style lang="scss" scoped>


ul{
    list-style-type: none;
    display: flex;
    justify-content: space-between;
    
}

li{
    margin-right: 2rem;
    font-size: 20px;
   
}

article{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 1rem;
}

    
</style>