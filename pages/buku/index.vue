<template>
    <div class="container-fluid">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">BUKU</h2>
                <nuxt-link to="/">
                <i class="bi bi-arrow-left"></i>
                </nuxt-link>
                <div class="my-3">
                    <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?">
                    </div>
                    <div class="my-3 textmuted">menampilkan 3 dari 3</div>
                    <div class="row">
                        <div class="col-lg-2">
                            <div class="card mb-3">
                                <nuxt-link to="/buku/des">
                                <div class="card-body">
                                    <img src="~/assets/img/cover1.jpg" class="cover" alt="cover 1">
                                </div>
                                </nuxt-link>
                            </div>
                        </div>
                        <div class="col-lg-2">
                            <div class="card mb-3">
                                <div class="card-body">
                                    <img src="~/assets/img/dikta.jpg" class="cover" alt="cover2">
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-2">
                            <div class="card mb-3">
                                <div class="card-body">
                                    <img src="~/assets/img/haru.jpg" class="cover" alt="cover3">
                                </div>
                            </div>
                        </div>
                    </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.card-body{
    width: 100%;
    height: 20em;
    padding: 0;
}

.cover {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: 0 30;
}
</style>