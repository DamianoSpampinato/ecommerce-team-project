<script>
    import ChosenForYou from './ChosenForYou.vue';
    import AppSpecialOffers from './AppSpecialOffers.vue';
    import ProductsCarousel from './ProductsCarousel.vue';
    export default{
        components:{
            ChosenForYou,
            AppSpecialOffers,
            ProductsCarousel
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
        <AppSpecialOffers></AppSpecialOffers>
        <ChosenForYou></ChosenForYou>
        
    </main>
</template>

<style lang="scss" scoped>
    @use '../style/partials/variables' as *;
main{
    background-color: #e4e5e7;
}
</style>