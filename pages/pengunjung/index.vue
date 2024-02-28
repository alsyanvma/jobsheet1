<template>
    <div class="container-fluid">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
                <nuxt-link to="/">
                <i class="bi bi-arrow-left"></i>
                </nuxt-link>
                <div class="my-3">
                    <input type="search" class="form-control from-control-lg rounded-5" placeholder="Filter...">
                    <div class="my-3 text-muted">menampilkan 1 dari 1</div>
                    <table class="table">
                        <thead>
                            <tr>
                                <td>#</td>
                                <td>NAMA</td>
                                <td>KEANGGOTAAN</td>
                                <td>WAKTU</td>
                                <td>KEPERLUAN</td>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1.</td>
                                <td>Alsya Novema</td>
                                <td>Siswa</td>
                                <td>26 Febuari 2024, 23.31.00</td>
                                <td>Baca</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>
