<template>
  <div>
    <!-- header section start  -->
    <header class="header">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-xl-12">
            <nav class="navbar navbar-expand-lg navbar-light">
              <nuxt-link class="navbar-brand" to="/">
                <img src="~/assets/images/logo.png" alt="logo">
              </nuxt-link>
              <button
                class="navbar-toggler"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                type="button"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div id="navbarSupportedContent" class="collapse navbar-collapse">
                <ul class="navbar-nav nav ml-auto">
                  <li class="nav-item">
                    <nuxt-link class="nav-link active" to="/">হোম
                    </nuxt-link>
                  </li>
                  <li class="nav-item">
                    <nuxt-link class="nav-link" to="/frontend-bootcamp">ফ্রন্টএন্ড বুটক্যাম্প</nuxt-link>
                  </li>
                  <li class="nav-item">
                    <nuxt-link class="nav-link" to="/backend-bootcamp">ব্যাকএন্ড বুটক্যাম্প</nuxt-link>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <!-- header section end  -->
    <Nuxt />
    <!-- footer section start -->
    <footer class="footer">
      <div class="container">
        <!-- start from here  -->
        <div class="footer-content">
          <!-- logo goes here -->
          <div class="footer__logo">
            <img src="~/assets/images/logo.png" alt="logo" class="img-fluid">
          </div>
          <!-- FOOTER MENU GOES HERE -->
          <ul class="footer__menues mb-0">
            <li>
              <nuxt-link to="/">হোম</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/frontend-bootcamp">ফ্রন্টএন্ড বুটক্যাম্প</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/backend-bootcamp">ব্যাকএন্ড বুটক্যাম্প</nuxt-link>
            </li>
          </ul>
          <ul class="footer__social-icon ml-0">
            <li><a href="https://www.facebook.com/codeshikhibd" target="__blank"><i class="fab fa-facebook-f"></i></a>
            </li>
            <li><a href="https://github.com/codeshikhi" target="__blank"><i class="fab fa-github"></i></a></li>
          </ul>
        </div>
      </div>
    </footer>
    <!-- footer section end -->
  </div>
</template>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  @import "~/assets/scss/main.scss";
</style>
