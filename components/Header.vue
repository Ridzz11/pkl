<template>
  <div class="he d-flex justify-content-center m-2" >
    <div class="row">
      <div class="col-2 pt-1"><img src="../assets/logo.png" alt=""></div>
      <div class="col pt-2">
        <h6>PT.DTHREE SUKSES MULIA </h6>
        <h7>JL.Linggajaya, Kab. Tasikmalaya, Jawa Barat.</h7>
      </div>
    </div>
</div>
  <nav class="navbar navbar-expand-lg navbar-light shadow py-4 d-flex justify-content-center">
    <div class="c">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse px-5" id="navbarNavDropdown">
        <ul class="navbar-nav mx-5 pt-2">
          <nuxt-link to="/">
            <li class="nav-item">
              <h6>BERANDA</h6>
            </li>
          </nuxt-link>
          <li class="nav-item mx-3">
            <nuxt-link to="/produk">
              <h6>PRODUK</h6>
            </nuxt-link>
          </li>
          <li class="nav-item mx-3">
            <nuxt-link to="/sarimbit">
              <h6>SARIMBIT</h6>
            </nuxt-link>
          </li>
          <li class="nav-item mx-3">
            <nuxt-link to="/about">
              <h6>ABOUT </h6>
            </nuxt-link>
          </li>
        </ul>
      </div>
         <div class="cari col-auto pt-4">
    <label class="visually-hidden" for="autoSizingSelect">Preference</label>
    <select class="form-select" id="autoSizingSelect">
      <option selected>MAU CARI APA NICH?</option>
      <option value="1">KEMKO ANAK</option>
      <option value="2">KEMKO DEWASA</option>
      <option value="3">GAMIS ANAK</option>
      <option value="3">GAMIS DEWASA</option>
    </select>
  </div>
    </div>
  </nav>
</template>
<style scoped>
img {
  height: 65px;
  margin-left: 9px;
}

li {
  font-family: sans-serif;
}
*{
  text-decoration: none;
  color: black;

}
.he{
  background-color: white;
}
.navbar{
  position: sticky;
  top :0;
  background-color: white;
  z-index: 1;
}
</style>