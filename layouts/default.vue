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
              <button class="navbar-toggler" @click.prevent="mobileNav = !mobileNav">
                <span v-if="!mobileNav" class="navbar-toggler-icon" />
                <svg
                  v-else
                  viewBox="0 0 24 24"
                  width="24"
                  height="24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="css-i6dzq1"
                ><line x1="18" y1="6" x2="6" y2="18" /><line x1="6" y1="6" x2="18" y2="18" /></svg>
              </button>
              <div class="collapse navbar-collapse" :class="{ 'show': mobileNav }">
                <ul class="navbar-nav nav ml-auto">
                  <li class="nav-item">
                    <nuxt-link class="nav-link" to="/" @click.native="mobileNav = false">
                      হোম
                    </nuxt-link>
                  </li>
                  <li class="nav-item">
                    <nuxt-link class="nav-link" :to="{ name: 'frontend-bootcamp' }" @click.native="mobileNav = false">
                      ফ্রন্টএন্ড বুটক্যাম্প
                    </nuxt-link>
                  </li>
                  <li class="nav-item">
                    <nuxt-link class="nav-link" :to="{ name: 'backend-bootcamp' }" @click.native="mobileNav = false">
                      ব্যাকএন্ড বুটক্যাম্প
                    </nuxt-link>
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
    <div class="skew-shape bg-light-gray">
      <!-- Got Question section Start -->
      <section id="book" class="absolute p-0">
        <div class="container">
          <div class="got-question bg-dark shadow-sm">
            <div class="got-question__info">
              <h5> ক্লাসে অংশগ্রহন করুন</h5>
              <p>
                ক্লাসে অংশ গ্রহন করার জন্য, প্রদত্ত ফর্ম ফিলাপ করতে হবে আপনাকে। <br> অতঃপর আমাদের প্রতিনিধি আপনার সাথে
                যোগাযোগ করবে, আপনার ভর্তির নিশ্চিত ব্যাপারে
              </p>
            </div>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSeEBvQDWwXKqxM5rph_JMviWpMHqUOWPrk_TP_kEPqS0PnBVQ/viewform" class="btn btn-light"> আপনার সিট বুক করুন </a>
          </div>
        </div>
      </section>
      <!-- Got Question section End -->

      <!-- footer section start -->
      <footer id="footer" class="footer">
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
                <nuxt-link to="/">
                  হোম
                </nuxt-link>
              </li>
              <li>
                <nuxt-link :to="{ name: 'frontend-bootcamp' }">
                  ফ্রন্টএন্ড বুটক্যাম্প
                </nuxt-link>
              </li>
              <li>
                <nuxt-link to="backend-bootcamp">
                  ব্যাকএন্ড বুটক্যাম্প
                </nuxt-link>
              </li>
            </ul>
            <ul class="footer__social-icon ml-0">
              <li>
                <a href="https://www.facebook.com/codeshikhibd" target="__blank" class="d-flex justify-content-center align-items-center">
                  <font-awesome-icon :icon="['fab', 'facebook-f']" style="width: 16px; height: 16px;" />
                </a>
              </li>
              <li>
                <a href="https://github.com/codeshikhi" target="__blank" class="d-flex justify-content-center align-items-center">
                  <font-awesome-icon :icon="['fab', 'github']" style="width: 16px; height: 16px;" />
                </a>
              </li>
            </ul>
          </div>
        </div>
      </footer>
      <!-- footer section end -->
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      mobileNav: false
    }
  }
}
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  @import "~/assets/scss/main.scss";
</style>
