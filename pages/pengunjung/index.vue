<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
                <div class="my-3">
                    <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
                </div>
                <div class="my-3 text-muted">menampilkan 1 dari 1</div>
                <table class="table">
                    <thead>
                        <tr>
                            <td>No</td>
                            <td>NAMA</td>
                            <td>KEANGGOTAAN</td>
                            <td>WAKTU</td>
                            <td>KEPERLUAN</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1.</td>
                            <td>Agni</td>
                            <td>Siswa</td>
                            <td>28 Februari 2024</td>
                            <td>Baca</td>
                        </tr>
                    </tbody>
                </table>
                <nuxt-link to="http://localhost:3000/">
                    <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">kembali</button>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>