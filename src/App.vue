<script>
    import AppHeader from './components/AppHeader.vue';
    import AppMain from './components/AppMain.vue';
    export default{
        components:{
            AppHeader,
            AppMain,
        }
    }
</script>

<template>
    <AppHeader></AppHeader>
    <AppMain></AppMain>
</template>

<style lang="scss">
@use './style/generic';

</style>
