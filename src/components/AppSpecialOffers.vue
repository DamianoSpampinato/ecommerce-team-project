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
                }, {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                }, {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                }, {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                }, {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                }, {
                    img: 'https://m.media-amazon.com/images/I/71gSG3FNBRL._AC_UL480_FMwebp_QL65_.jpg',
                    name: 'Carpuride W702 Senza Fili',
                    price: 200,
                    discount: 15,
                },
            ]
        }
    }
}
</script>

<template>
<div class="ms-container bg-white">
    <div class="d-flex align-items-end gap-3 mb-2">
        <h5 class="m-0 fw-bold">Offerte lampo</h5>
        <small><a href="#">scopri di più</a></small>
    </div>
    <div class="d-flex">
        <div 
        v-for="item in itemsArray"
        class="card ms-card-width p-2 border-0">
        <img :src="`${item.img}`" class="card-img-top" alt="...">
        <div class="card-body">
            <div class="item-name">
                {{ item.name }}
            </div>
            <div class="discount">
                <span class="banner-discount text-white p-1">{{ item.discount }} di sconto</span>
                <span class="color-red">Offerta a tempo</span>
            </div>
            <div class="price">
                <span>
                    {{ item.price - ( item.price * item.discount / 100)  }}
                </span>
                <small>€ Più basso: </small>
                <small class="line-through">{{ item.price }}€</small>
            </div>
        </div>
    </div>
</div>
</div>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;
.color-red{
    color: $red-bg;
    font-size: 12px;
    font-weight: bold;
    margin-left: 3px;
}
.banner-discount{
    background-color: $red-bg;
    font-size: 12px;
}
.line-through{
    text-decoration:line-through;
}
.ms-card-width{
    width: calc(100% / 6);
}
.bg-white{
    background-color: white;
}
a{
    text-decoration: none;
    color: $green-azure-bg;
    font-weight: 500;
}
</style>