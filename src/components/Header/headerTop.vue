<script>

    export default {
        name: 'headerTop'
    }

</script>

<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid align-items-center text-white">
            <a class="navbar-brand" href="#">
                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" alt="Bootstrap" width="100" height="50">
            </a>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item ps-3 pe-2">
                        <h5>Invia a (nome utente)</h5>
                        <h5><i class="fa-solid fa-location-dot"></i>(via)</h5>
                    </li>
                </ul>
                <div class="input-group mb-3 w-100">
                    <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">Tutte le categorie</button>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Giochi</a></li>
                        <li><a class="dropdown-item" href="#">Abbigliamento</a></li>
                        <li><a class="dropdown-item" href="#">Macchine fotografiche</a></li>
                    </ul>
                    <input type="text" class="form-control" aria-label="Text input with dropdown button">
                    <span class="input-group-text" id="addon-wrapping"><i class="fa-solid fa-magnifying-glass"></i></span>
                </div>
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item px-3">
                        <span>Ciao (nome utente)</span>
                    <div class="btn-group mt-1">
                        <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">Account & liste</button>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Menu item</a></li>
                            <li><a class="dropdown-item" href="#">Menu item</a></li>
                            <li><a class="dropdown-item" href="#">Menu item</a></li>
                        </ul>
                    </div>
                    </li>
                    <li class="nav-item pe-4">
                        <a href="#">Resi e ordini</a>
                    </li>
                    <li class="nav-item">
                        <span>(count oridni)</span>
                        <i class="fa-solid fa-cart-shopping"></i>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
    nav{
        background-color:#141920 !important;
    }
</style>
