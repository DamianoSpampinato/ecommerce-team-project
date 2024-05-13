<script>
export default{
    name: 'AppSpecialOffers',
    data(){
        return{
            itemsArray:[
                {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                }
            ]
        }
    }
}
</script>

<template>
<div class="ms-container bg-secondary">
    <div class="d-flex align-items-end gap-1">
        <h5 class="m-0">Offerte lampo</h5>
        <small><a href="#">scopri di più</a></small>
    </div>
    <div 
    v-for="item in itemsArray"
    class="card" style="width: 18rem;">
        <img :src="`${item.img}`" class="card-img-top" alt="...">
        <div class="card-body">
            <div class="item-name">
                {{ item.name }}
            </div>
            <div class="discount">
                <span class="banner-discount text-white">{{ item.discount }} di sconto</span>
                <span class="color-red">Offerta lampo</span>
            </div>
            <div class="price">
                <span>
                    {{ item.price - ( item.price * item.discount / 100)  }}
                </span>
                <small>€ Più basso:</small>
                <small class="line-through">{{ item.price }}€</small>
            </div>
        </div>
    </div>
</div>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;
.color-red{
    color: $red-bg;
}
.banner-discount{
    background-color: $red-bg;
}
.line-through{
    text-decoration:line-through;
}
</style>