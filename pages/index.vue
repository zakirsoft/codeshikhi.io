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
                <nuxt-link class="btn btn-primary btn-wide mr-4 mb-2" :to="{ name: 'frontend-bootcamp' }">
                  ফ্রন্টএন্ড বুটক্যাম্প
                  <i class="fas fa-angle-right fa-sm ml-1" />
                </nuxt-link>
                <nuxt-link class="btn btn-dark btn-wide mb-2" :to="{ name: 'backend-bootcamp' }">
                  ব্যাকএন্ড বুটক্যাম্প
                  <i class="fas fa-angle-right fa-sm ml-1" />
                </nuxt-link>
              </div>
              <!-- <span class="banner__small">Start free trial. * No credit card required.</span> -->
            </div>
          </div>
          <div class="col-md-12 col-lg-6 order-1 order-md-0">
            <div class="banner__image mt-5">
              <img src="~/assets/images/banner.svg" alt="Bannr_image" class=" img-fluid">
            </div>
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
                আমাদের চলমান <span>বুটক্যাম্প</span> সমূহ
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <div class="bootcamp-block">
              <div class="header">
                <div class="title">
                  <div class="icon">
                    <font-awesome-icon :icon="['fas', 'code']" />
                  </div>
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
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>HTML</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>CSS</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>JavaScript</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Bootstrap</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>SCSS</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>React & Vue.js</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Git & Github</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Server Mangement</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Upwork Guidline</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Fiverr Guidline</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Resume Building</p>
                  </li>
                </ul>
              </div>
              <div class="footer">
                <div class="info">
                  <h5>সম্পূর্ণ ৭২ ঘন্টা (৩ মাস)</h5>
                  <p>সপ্তাহে ৩ দিন ২ ঘন্টা করে</p>
                </div>
                <nuxt-link class="btn btn-primary btn-outline-primary" :to="{ name: 'frontend-bootcamp' }">
                  বিস্তারিত দেখুন
                </nuxt-link>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-12 col-md-12 col-lg-6">
            <div class="bootcamp-block">
              <div class="header">
                <div class="title">
                  <div class="icon">
                    <font-awesome-icon :icon="['fas', 'code']" />
                  </div>
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
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>PHP</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>MySQL</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>PHP OOP</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Laravel</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>REST API</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Vue.js</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Git & Github</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Server Mangement</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Upwork Guidline</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Fiverr Guidline</p>
                  </li>
                  <li>
                    <div class="icon icon-success">
                      <font-awesome-icon :icon="['fas', 'check']" />
                    </div>
                    <p>Resume Building</p>
                  </li>
                </ul>
              </div>
              <div class="footer">
                <div class="info">
                  <h5>সম্পূর্ণ ৭২ ঘন্টা (৩ মাস)</h5>
                  <p>সপ্তাহে ৩ দিন ২ ঘন্টা করে</p>
                </div>
                <nuxt-link class="btn btn-primary btn-outline-primary" :to="{ name: 'backend-bootcamp' }">
                  বিস্তারিত দেখুন
                </nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Bootcamps section end -->
    <Team />
  </div>
</template>

<script>
import Team from '~/components/Team'

export default {
  components: {
    Team
  }
}
</script>

<style></style>
