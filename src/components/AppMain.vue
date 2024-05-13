<script>
    import ChosenForYou from './ChosenForYou.vue';
    import AppSpecialOffers from './AppSpecialOffers.vue'
    export default{
        components:{
            ChosenForYou,
            AppSpecialOffers
        },
        data(){
            return{

            }
        },
    }
</script>

<template>
    <main>
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