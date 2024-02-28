<template>
    <div class="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung/tambah">
                    <div class="card bg-pengunjung rounded-5">
                        <div class="card-body">
                            <h2>Pengunjung</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>

            <div class="col-lg-6">
                <nuxt-link to="/buku">
                    <div class="card bg-buku rounded-5">
                        <div clas="card-body">
                            <h2>Cari Buku</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </div>
    <h1 class="statistik">STATISTIK</h1>
    
    <div class="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung">
                <div class="card bg-warning rounded-5">
                <div class="card-body">
                    <h3>32 Pengunjung</h3>
                </div>
                </div>
                </nuxt-link>
            </div>
            <div class="col-lg-6">
                <nuxt-link to="/buku">
                <div class="card bg-success rounded-5">
                    <div class="card-body">
                        <h4>180 Buku</h4>
                    </div>
                </div>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>


<style scoped>
.card {
    height: 250px;
    box-shadow: 1px 1px 10px #424242;
}

.card.bg-pengunjung {
    background-image: url('../assets/img/bg-home-kunjungan.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    opacity: 90;
}

.card.bg-buku {
    background-image: url('../assets/img/bg-home-cari-buku.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    opacity: 90%;
}

h2 {
    color: black;
    opacity: 100%;
}

h1 {
    color: black;
}

h3 {
    color: black;
    font-size: 70px;
    text-align: center;
    margin: 40px;
}

h4 {
    color: black;
    font-size: 70px;
    text-align: center;
    margin: 40px;
}
</style>