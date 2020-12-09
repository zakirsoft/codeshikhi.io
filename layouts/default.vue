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
    <!-- Trainer section start -->
    <section class="trainer">
      <div class="container ">
        <div class="row">
          <div class="col-12">
            <div class="trainer-title text-center">
              <h6> আমাদের দক্ষ প্রশিক্ষক </h6>
              <h4> পেশাদারদের বিশ্বাস করুন </h4>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-sm-6 col-md-6 col-lg-3">
            <div class="trainer-area">
              <div class="trainer-area__image">
                <img src="~/assets/images/team/Zakir.jpg" alt="trainer" class="img-fluid">
              </div>
              <div class="trainer-area__info text-center">
                <h5>জাকির হোসেন</h5>
                <p>ট্রেইনার</p>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-3">
            <div class="trainer-area">
              <div class="trainer-area__image">
                <img src="~/assets/images/team/Rashed.jpg" alt="trainer" class="img-fluid">
              </div>
              <div class="trainer-area__info text-center">
                <h5>শেখ রাশেদ</h5>
                <p>ট্রেইনার</p>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-3">
            <div class="trainer-area">
              <div class="trainer-area__image">
                <img src="~/assets/images/team/jahid.jpg" alt="support" class="img-fluid">
              </div>
              <div class="trainer-area__info text-center">
                <h5>জাহিদ ইসলাম</h5>
                <p>সাপোর্ট</p>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-md-6 col-lg-3">
            <div class="trainer-area">
              <div class="trainer-area__image">
                <img src="~/assets/images/team/Partho.jpg" alt="support" class="img-fluid">
              </div>
              <div class="trainer-area__info text-center">
                <h5>পার্থ হালদার</h5>
                <p>সাপোর্ট</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Trainer section end -->
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
              <img src="~/assets/images/logo.png" alt="logo" class="img-fluid">
            </div>
            <!-- FOOTER MENU GOES HERE -->
            <ul class="footer__menues mb-0">
              <li><nuxt-link to="/">হোম</nuxt-link></li>
              <li><nuxt-link to="/frontend-bootcamp">ফ্রন্টএন্ড বুটক্যাম্প</nuxt-link></li>
              <li><nuxt-link to="/backend-bootcamp">ব্যাকএন্ড বুটক্যাম্প</nuxt-link></li>
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
