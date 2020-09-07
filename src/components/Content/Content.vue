
<script>
import Home from './Home/Home.vue'
import Presentation from './Presentation/Presentation.vue'
import Formation from './Formation/Formation.vue'
import Portfolio from './Portfolio/Portfolio.vue'

export default {
    name: 'ContentPortfolio',
    components: {
        Home,
        Presentation,
        Formation,
        Portfolio
    }
}
</script>

<template>
    <div class="md-content">
        <Home/>
        <Presentation/>
        <Formation/>
        <Portfolio/>
    </div>

</template>

<style>
    @import './Contenu.css';
</style>