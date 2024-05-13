<script>
    import ChosenForYou from './ChosenForYou.vue';
    export default{
        components:{
            ChosenForYou,
        },
        data(){
            return{

            }
        },
    }
</script>

<template>
    <main>
        <ChosenForYou></ChosenForYou>
    </main>
</template>

<style lang="scss" scoped>
    @use '../style/partials/variables' as *;
</style>