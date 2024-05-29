<script>
export default {
    name: 'ProductsCarousel'
}

</script>

<template>
    <div class="ms-container">
        <div class="ms-carousel">
            <div class="d-flex gap-3 mb-2">
                <h5 class="fw-bold">Scopri i prodotti Made in Italy</h5>
                <small><a href="#">scopri</a></small>
            </div>
          <div id="carouselExample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active ms-card">
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://home.isaproject.it/83541-mobile_large_default/lampada-terra-design-woody.jpg" class="d-block w-100" alt="...">
                    </div>
                </div>
                <div class="carousel-item ms-card">
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="ms-prod-card">
                        <img src="https://www.pngall.com/wp-content/uploads/5/Purse-PNG-Image-HD.png" class="d-block w-100" alt="...">
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../style/partials/variables' as *;
.ms-carousel{
    background-color: white;
    margin-bottom: 20px;
    a{
    text-decoration: none;
    color: $green-azure-bg;
    font-weight: 500;
    }
}
.ms-card{
    display: flex;
    .ms-prod-card{
        img{
            width: calc(100% / 6);
        }
    }
}
</style>