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
  </div>
</template>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  @import "~/assets/scss/main.scss";
</style>
