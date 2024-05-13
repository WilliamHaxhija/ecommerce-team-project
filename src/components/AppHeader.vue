<script>
export default {
    name: 'COMPONENT'
}
</script>

<template>
    <header>
        <div class="container-fluid d-flex align-items-center justify-content-center">
            <div class="row">
                <div class="col-2">
                    <div class="logo w-100">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" class="w-100" alt="logo">
                    </div>
                </div>
                <div class="col-8">
                    <div class="input-group mb-3 w-100">
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
                <div class="col-2"></div>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">

</style>
