<template>
  <div>
    <!-- header section start  -->
    <header class="header">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-xl-12">
            <nav class="navbar navbar-expand-lg navbar-light">
              <a class="navbar-brand" href="index.html">
                <img src="~/assets/images/logo.png" alt="logo">
              </a>
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
                    <a class="nav-link active" href="index.html">হোম
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="frontend-bootcamp.html">ফ্রন্টএন্ড বুটক্যাম্প</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="backend-bootcamp.html">ব্যাকএন্ড বুটক্যাম্প</a>
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
    <!-- call to action section end -->
    <div class="skew-shape bg-light-gray">
      <!-- Got Question section Start -->
      <section class="absolute p-0">
        <div class="container">
          <div class="got-question bg-dark shadow-sm">
            <div class="got-question__info">
              <h5> ক্লাসে জয়েন করুন </h5>
              <p> আমাদের সাথে ক্লাস করার জন্য, এখনই রেজিষ্ট্রেশন করে ফেলুন।</p>
            </div>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSeEBvQDWwXKqxM5rph_JMviWpMHqUOWPrk_TP_kEPqS0PnBVQ/viewform" class="btn btn-light btn-lg"> আপনার সিট বুক করুন </a>
          </div>
        </div>
      </section>
      <!-- Got Question section End -->

      <!-- footer section start -->
      <footer class="footer">
        <div class="container">
          <!-- start from here  -->
          <div class="footer-content">
            <!-- logo goes here -->
            <div class="footer__logo">
              <img src="assets/images/logo.png" alt="logo" class="img-fluid">
            </div>
            <!-- FOOTER MENU GOES HERE -->
            <ul class="footer__menues mb-0">
              <li><a href="index.html"> হোম </a></li>
              <li><a href="frontend-bootcamp.html"> ফ্রন্টএন্ড বুটক্যাম্প </a> </li>
              <li><a href="backend-bootcamp.html"> ব্যাকএন্ড বুটক্যাম্প </a> </li>
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
  </div>
</template>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  @import "~/assets/scss/main.scss";
</style>
