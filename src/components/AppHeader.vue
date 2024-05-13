<script>
</script>

<template>
    <header>
        <div class="ms-header-container">
            <div class="ms-row d-flex align-items-center py-1">
                <!-- header top left -->
                <div class="ms-header-top-left d-flex">
                    <div class="ms-logo-container d-flex align-items-center mx-2">
                    <img class="img-fluid"
                        src="https://cdn.vectorstock.com/i/500p/74/63/amazon-logo-background-icon-vector-50147463.jpg"
                        alt="">
                    </div>
                    <div class="ms-send-to mx-2">
                        <div>Invia a</div>
                        <div class="text-white"><i class="fa-solid fa-location-dot"></i></div>
                    </div>
                </div>
                <!--/ header top left -->
                <!-- header top center -->
                <div class="ms-header-top-center flex-grow-1 mx-3">
                    <div class="ms-input-container mx-2 ">
                        <div class="input-group">
                            <button class="btn btn-outline-secondary dropdown-toggle" type="button"
                                data-bs-toggle="dropdown" aria-expanded="false">Dropdown</button>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                                <li><a class="dropdown-item" href="#">Another action</a></li>
                                <li><a class="dropdown-item" href="#">Something else here</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Separated link</a></li>
                            </ul>
                            <input type="text" class="form-control" aria-label="Text input with dropdown button">
                            <button class="btn btn-outline-secondary" type="button" id="button-addon2"><i class="fa-solid fa-magnifying-glass"></i></button>
                        </div>
                    </div>
                </div>
                <!--/ header top center -->
                <!-- header top-right -->
                <div class="ms-header-top-right d-flex flex-grow-1 ms-auto justify-content-end gap-3 mx-2">
                    <div class="">Account e liste</div>
                    <div class="">Resi e ordini</div>
                    <div>Carrello</div>
                </div>
                <!--/ header top-right -->
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use'../style/partials/_variables' as *;

.ms-header-container {
    background-color: coral;
    width: 100%;
}



.ms-logo-container {
    width: 100px
}
.ms-header-top-center{
    width: 50%;
}

.ms-header-top-right {
    width: 15%;
}
</style>