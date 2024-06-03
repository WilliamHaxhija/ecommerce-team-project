<script>

    export default {
        name: 'MadeInItaly'
    }

</script>

<template>
    <div class="container mt-3">
        <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="row m-2 text-center">
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img1.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 1</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img2.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 2</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img3.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 3</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img1.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 4</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img2.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 5</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../../assets/img/madeinitaly/img3.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 6</h5>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
                <div class="carousel-item">
                    <div class="row m-2 text-center">
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img1.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 7</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img2.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 8</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img3.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 9</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img1.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 10</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img2.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 11</h5>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-2">
                            <div class="card" style="width: 18rem;">
                                <img src="../assets/img/madeinitaly/img3.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Card 12</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="false"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="false"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>

<style scoped>
.container{
    background-color: white;
}
.carousel-item {
    width: 100%;
}

.card {
    width: 100% !important;
    margin: 10px;
    border: none;
    img {
        border-radius: 50%;
    }
}

.carousel-inner.row {
    margin-left: -10px;
}
</style>