<script>
</script>

<template>
    <header>
        <div class="ms-header-container">
            <div class="ms-row d-flex align-items-center py-2">
                <div class="ms-logo-container">
                    <img class="img-fluid"
                        src="https://cdn.vectorstock.com/i/500p/74/63/amazon-logo-background-icon-vector-50147463.jpg"
                        alt="">
                </div>
                <div class="ms-send-to">
                    <div>Invia a</div>
                    <div class="text-white"><i class="fa-solid fa-location-dot"></i></div>
                </div>
                <div class="ms-input-container">
                    <div class="input-group mb-3">
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
                    </div>
                </div>
                <div>Account e liste</div>
                <div>Resi e ordini</div>
                <div>Carrello</div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use'../style/partials/_variables' as *;

.ms-header-container {
    background-color: coral;
}

.ms-logo-container {
    width: 15%;
}

.ms-input-container {

}
</style>