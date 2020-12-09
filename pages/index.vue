<template>
  <div>
    <!-- banner section start  -->
    <section class="banner">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-12 col-lg-6 order-2 order-md-0">
            <div class="banner__content">
              <h1 class="banner__heading">
                ওয়েব ডেভেলপমেন্ট শিখে স্থায়ী ক্যারিয়ার গড়ে তুলুন
              </h1>
              <p class="banner__pra">
                ওয়েভ ডেভেলপমেন্ট এর বিষয়ে বিস্তারিত প্রশিক্ষণ এবং গাইডলাইন নিয়ে
                আমাদের ক্যারিয়ার ডেভেলমেন্ট বুটক্যাম্প ।
              </p>
              <div class="banner__button mt-5 mb-2">
                <a class="btn btn-primary btn-wide mr-4 mb-2" href="frontend-bootcamp.html">ফ্রন্টএন্ড বুটক্যাম্প
                  <i class="fas fa-angle-right fa-sm ml-1"></i></a>
                <a class="btn btn-dark btn-wide mb-2" href="backend-bootcamp.html">
                  ব্যাকএন্ড বুটক্যাম্প
                  <i class="fas fa-angle-right fa-sm ml-1"></i></a>
              </div>
              <!-- <span class="banner__small">Start free trial. * No credit card required.</span> -->
            </div>
          </div>
          <div class="col-md-12 col-lg-6 order-1 order-md-0">
            <div class="banner__image mt-5"><img src="~/assets/images/banner.svg" alt="Bannr_image" class=" img-fluid" /></div>
          </div>
        </div>
      </div>
    </section>
    <!-- banner section end  -->
    <!-- Bootcamps section start -->
    <section class="bootcamp bg-light-gray">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="section____info">
              <h2 class="heading-title">
                আমাদের চলমান <span>বুটক্যাম্প</span>সমূহ
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <div class="bootcamp-block">
              <div class="header">
                <div class="title">
                  <div class="icon"><i class="fas fa-code"></i></div>
                  <p>ফ্রন্টএন্ড বুটক্যাম্প</p>
                </div>
                <p>
                  আধুনিক টেকনোলজির সম্বনয়ে ফ্রন্টএন্ড ডেভেলপমেন্ট কোর্স টি ডিজাইন
                  করা হয়েছে । এই কোর্স টির মাধ্যম্যে, আপনাকে যেকোন ওয়েভসাইট ডিজাইন
                  করার সক্ষম করে তোলা হবে। এর পাশাপাশি চাকরি বাজার এবং
                  ফ্রিল্যান্সিং ক্যারিয়ারের বিষয়ে গাইডলাইন পাবেন।
                </p>
              </div>
              <div class="body">
                <!-- <p class="headline"> আপনি যা যা শিখবেন </p> -->
                <ul class="check-list">
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>HTML</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>CSS</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>JavaScript</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Bootstrap</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>SCSS</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>React & Vue.js</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Git & Github</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Server Mangement</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Upwork Guidline</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Fiverr Guidline</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Resume Building</p>
                  </li>
                </ul>
              </div>
              <div class="footer">
                <div class="info">
                  <h5>সম্পূর্ণ ৭২ ঘন্টা (৩ মাস)</h5>
                  <p>সপ্তাহে ৩ দিন ২ ঘন্টা করে</p>
                </div>
                <a class="btn btn-primary btn-outline-primary" href="frontend-bootcamp.html">
                  বিস্তারিত দেখুন
                </a>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <div class="bootcamp-block">
              <div class="header">
                <div class="title">
                  <div class="icon"><i class="fas fa-code"></i></div>
                  <p>ব্যাকএন্ড বুটক্যাম্প</p>
                </div>
                <p>
                  আমাদের এই কোর্সটি লারাভেল ফ্রেমওয়ার্ক এ বেস করে ডিজাইন করা
                  হয়েছে। এই কোর্স এর মূল লক্ষ্য হলো আপনার মধ্যে ওয়েভসাইট/ওয়েভ
                  এপ্লিকেশন ডেভেলপমেন্ট করার সক্ষমতা তৈরী করা। এর পাশাপাশি চাকরি
                  বাজার এবং ফ্রিল্যান্সিং ক্যারিয়ারের বিষয়ে গাইডলাইন পাবেন।
                </p>
              </div>
              <div class="body">
                <ul class="check-list">
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>PHP</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>MySQL</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>PHP OOP</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Laravel</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>REST API</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Vue.js</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Git & Github</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Server Mangement</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Upwork Guidline</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Fiverr Guidline</p>
                  </li>
                  <li>
                    <font-awesome-icon :icon="['fas', 'check']"/>
                    <p>Resume Building</p>
                  </li>
                </ul>
              </div>
              <div class="footer">
                <div class="info">
                  <h5>সম্পূর্ণ ৭২ ঘন্টা (৩ মাস)</h5>
                  <p>সপ্তাহে ৩ দিন ২ ঘন্টা করে</p>
                </div>
                <a class="btn btn-primary btn-outline-primary" href="backend-bootcamp.html">
                  বিস্তারিত দেখুন
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Bootcamps section end -->
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
  </div>
</template>

<script>
// export default {};
</script>

<style></style>
