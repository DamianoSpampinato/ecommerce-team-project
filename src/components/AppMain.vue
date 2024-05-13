<script>
import ProductsCarousel from './ProductsCarousel.vue';
    export default{
        components:{
            name: 'AppMain'
        },
        data(){
            return{

            }
        },
    }
</script>
<template>
    <main>
        <ProductsCarousel></ProductsCarousel>
    </main>
</template>

<style lang="scss" scoped>
    @use '../style/partials/variables' as *;
</style>