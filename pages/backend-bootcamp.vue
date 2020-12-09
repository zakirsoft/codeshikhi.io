<template>
  <div>
    <!-- banner section start  -->
    <section class="subbanner bg-light-gray">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-10 col-12 col-lg-8">
            <div class="subbanner__content">
              <div class="btn-xs bg-color d-inline-block btn-pill text-uppercase mb-2">Trending</div>
              <h1 class="subbanner__header"> মাস্টারিং ব্যাকএন্ড ডেভেলপার বুটক্যাম্প </h1>
              <p class="subbanner__pra mb-3"> পেশাদারদের মত দক্ষতা অর্জন করুন, বেসিক থেকে শুরু করে ‍আপনার
                নিজের ওয়েভসাইট ডিজাইন করা পর্যন্ত। </p>
              <div class="d-flex align-items-center flex-wrap">
                <!-- Authors -->
                <div class="d-flex align-items-center mr-4">
                  <div class="avatar-group">
                    <span class="avatar avatar-xs avatar-circle">
                      <img class="avatar-img" src="~/assets/images/team/Zakir.jpg" alt="Image Description">
                    </span>
                  </div>
                  <span class="pl-2">Created by<a class="link-underline ml-1" target="_blank" href="https://zakirhossen.com">Zakir Hossen</a></span>
                </div>
                <!-- End Authors -->
                <!-- Rating -->
                <div class="d-flex align-items-center flex-wrap">
                  <ul class="list-inline mt-n1 mb-0 mr-2">
                    <li class="list-inline-item mx-0">
                      <img src="~/assets/images/star.svg" alt="Review rating" width="16">
                    </li>
                    <li class="list-inline-item mx-0">
                      <img src="~/assets/images/star.svg" alt="Review rating" width="16">
                    </li>
                    <li class="list-inline-item mx-0">
                      <img src="~/assets/images/star.svg" alt="Review rating" width="16">
                    </li>
                    <li class="list-inline-item mx-0">
                      <img src="~/assets/images/star.svg" alt="Review rating" width="16">
                    </li>
                    <li class="list-inline-item mx-0">
                      <img src="~/assets/images/star-half.svg" alt="Review rating" width="16">
                    </li>
                  </ul>
                  <span class="d-inline-block">
                    <span class="text-dark font-weight-bold mr-1">4.87</span>
                    <span class="text-muted">(1.5k+ reviews)</span>
                  </span>
                </div>
                <!-- End Rating -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- banner section end  -->
    <!-- features section start -->
    <section class="features">
      <div class="container">
        <div class="row">
          <div class="features__section text-center">
            <span class="text-uppercase d-inline-block mb-2"> সুবিধা সমূহ </span>
            <h2> বুটক্যাম্প টি আপনার জন্য নিখুত শুরুর জায়গা হতে পারে </h2>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-5 col-md-12 col-sm-12 mb-5">
            <div class="mb-5">
              <div class="icon-box mt-3">
                <font-awesome-icon :icon="['fas', 'user']"/>
              </div>
              <h3> চমৎকার কিছু বৈশিষ্ট্য </h3>
              <p> এক নজরে দেখে নিন, বুটক্যাম্প এর আকর্ষনীয় কিছু বৈশিষ্ট্য </p>
            </div>
            <ul class="check-list">
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> HTML </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> CSS </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> JavaScript </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> Bootstrap </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> SCSS </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> React & Vue.js </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> Git & Github </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']"/>
                <p> Server Mangement </p>
              </li>
            </ul>
          </div>
          <div class="col-lg-7 col-md-12 col-sm-12">
            <div class="position-relative">
              <div class="bootcamp-block  bootcamp-skew__30 featurescard">
                <div class="header">
                  <div class="title">
                    <div class="icon">
                      <font-awesome-icon :icon="['fas', 'code']" />
                    </div>
                    <p> ব্যাকএন্ড বুটক্যাম্প </p>
                  </div>
                  <p> আমাদের এই কোর্সটি লারাভেল ফ্রেমওয়ার্ক এর বেস করে ডিজাইন করা হয়েছে। এই কোর্স এর মূল
                    লক্ষ্য হলে আপনার মধ্যে ওয়েভসাইট ডেভেলপমেন্ট করার সক্ষমতা তৈরী করা। এর পাশাপাশি চাকরি
                    বাজার এবং ফ্রিল্যান্সিং ক্যারিয়ারের বিষয়ে গাইডলাইন পাবেন। </p>
                </div>
                <div class="body">
                  <!-- <p class="headline"> আপনি যা যা শিখবেন </p> -->
                  <ul class="check-list">
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> PHP </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> MySQL </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> PHP OOP </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']"/>
                      <p> Laravel </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']"/>
                      <p> REST API </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Vue.js </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Git & Github </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Server Mangement </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Upwork Guidline </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Fiverr Guidline </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> Resume Building </p>
                    </li>
                  </ul>
                </div>
                <div class="footer">
                  <div class="info">
                    <h5>সম্পূর্ণ ৭২ ঘন্টা (৩ মাস)</h5>
                    <p>সপ্তাহে ৩ দিন ২ ঘন্টা করে</p>
                  </div>
                  <a class="btn btn-primary btn-outline-primary" href="backend-bootcamp.html"> বিস্তারিত
                    দেখুন </a>
                </div>
              </div>

              <!-- SVG Elements -->
              <div class="dot-shape">
                <img src="~/assets/images/dots-2.svg" alt="shape">
              </div>
              <!-- End SVG Elements -->
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- features section End -->
    <!--  how-we-go section start  -->
    <section class="go bg-dark">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="section__info">
              <h2 class="section_title"> বোনাস সুবিধা গুলো </h2>
              <div class="section_brief"> আমাদের চমৎকার কিছু কার্যক্রম শুধু মাত্র কোর্সে ভর্তি হয়ে আপনিও পেতে পারেন
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'user']"/>
              </span>
              <h6 class="go_title">
                এক্সপার্টদের কাছ থেকে শিখুন
              </h6>
              <div class="go_brief">
                <!-- HATH EEH KOLOM ER MOTO KORE APNAKEY OVVIGGOH KORE TULA HOBEY , APNAR CAREER BUILD UP ER JONNO  -->
                অভিজ্ঞতা সর্বদাই গুরুত্বপূর্ণ ভূমিকা পালন করে, আর আপনি সঠিক জায়গায় এসেছেন কারন আমাদের প্রশিক্ষকদের রয়েছে
                <b>৪+</b> বছরের বেশী কাজ করার অভিজ্ঞতা।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'graduation-cap']"/>
              </span>
              <h6 class="go_title">
                ইন্টার্নশিপ সুবিধা
              </h6>
              <div class="go_brief">
                সঠিক ভাবে কোর্স সম্পূর্ণ করার পর, প্রত্যেক ব্যাচ থেকে আমরা ২ জন ছাত্র/ছাত্রী কে ইন্টার্নশিপ সুবিধা
                প্রদান করব ।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'globe']"/>
              </span>
              <h6 class="go_title">
                বিনামুল্যে পোর্টফলিও ওয়েভসাইট
              </h6>
              <div class="go_brief">
                আমরা আপনার পোর্টফলিও তৈরী করতে সাহায্য করব এবং আপনাকে একটি পোর্টফলিও ওয়েভসাইট ডিজাইন ফ্রিতে দেওয়া হবে ।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'list']"/>
              </span>
              <h6 class="go_title">
                বিনামুল্যে চিটশিট
              </h6>
              <div class="go_brief">
                HTML, CSS, JavaScript, Git, VSCode,Bootstrap </b> এর যাবতীয় চিটশিট প্রদান করা হবে। যা কোর্স চলাকালীন
                সময়ে শিক্ষার্থীদের সহায়ক হবে।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'dollar-sign']"/>
              </span>
              <h6 class="go_title">
                ফ্রিল্যান্সিং গাইডলাইন
              </h6>
              <div class="go_brief">
                ফ্রিল্যান্সিং সম্পর্কে ফ্রিল্যান্সারদের থেকে সেরা গাইডলাইন আর কেও দিতে পারবে না। আমাদের প্রশিক্ষকদের
                রয়েছে ফ্রিল্যান্সিং এর অভিজ্ঞতা ।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'briefcase']"/>
              </span>
              <h6 class="go_title">
                কর্পোরেট জব পেতে সাহায্য
              </h6>
              <div class="go_brief">
                এই বুটক্যাম্পটি আপনাকে সিভি, পোর্টফলিও তৈরীতে এবং কর্পোরেট জব এর জন্য প্রস্তুত হতে সহযোগিতা করবে ।
              </div>
            </div>
          </div>
        </div>

        <div class="row pt-5">
          <div class="col-12">
            <ul class="go__btns">
              <li><a href="#" class="btn btn-primary"> আপনার সিট টি বুক করুন </a></li>
              <li><a href="#">or</a></li>
              <li><a href="#syllabus" class="btn btn-primary"> সিলেবাস দেখুন </a></li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!--  how-we-go section end  -->
    <!-- platform section start -->
    <section class="platform">
      <div class="container">
        <div class="row">
          <div class="col-lg-5 col-md-6 col-sm-12">
            <div class="platform__title mb-5">
              <span>টুলস</span>
              <h3> একনজরে প্রযুক্তি গুলো</h3>
            </div>
          </div>
          <div class="col-lg-7 col-md-6 col-sm-12">
            <div class="platform__list">
              <div class="platform__logo platform__logo-one">
                <img src="~/assets/images/technology/html.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-two">
                <img src="~/assets/images/technology/css.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-three">
                <img src="~/assets/images/technology/javaScript.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-four">
                <img src="~/assets/images/technology/bootstrap.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-five">
                <img src="~/assets/images/technology/scss.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-six">
                <img src="~/assets/images/technology/git.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-seven">
                <img src="~/assets/images/technology/github.svg" alt="logo">
              </div>
              <div class="platform__logo platform__logo-eight">
                <img src="~/assets/images/technology/react.svg" alt="logo" class="img-fluid">
              </div>
              <div class="platform__logo platform__logo-nine">
                <img src="~/assets/images/technology/vue.svg" alt="logo" class="img-fluid">
              </div>
            </div>
          </div>
        </div>
        <div class="bg-dark mt-2 w-100" style="height: 5px;"></div>
      </div>
    </section>
    <!-- platform section end -->
    <!-- syllabus section start  -->
    <section class="syllabus" id="syllabus">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="trainer-title text-center">
              <h6> কোর্স সিলেবাস </h6>
              <h4> ৩ মাসের কোর্স প্ল্যান </h4>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6 col-md-12">
            <div class="mb-5">
              <h3> আপনার জীবন বদলে দিতে পারে এই সিলেবাস </h3>
              <p> ফ্রন্টএন্ড ডেভেলপার হওয়ার জন্য এ টু জেড গাইডলাইন নিয়ে আমাদের বানানো চমৎকার সিলেবাস। </p>
            </div>
            <div class="row">
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> 36 </h4>
                  <p> সর্বমোট ক্লাস </p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> 72 </h4>
                  <p> সর্বমোট ঘন্টা </p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> 21 </h4>
                  <p> সর্বমোট প্রজেক্ট </p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> 136 </h4>
                  <p> স্টুডেন্ট ভর্তি </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6 col-md-12">
            <div class="syllabus-data">
              <div class="toggle active">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text">PHP, OOP & Database</h6>
                  </div>
                  <h6 class="lecture-count">
                    6 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Basics Part 1 - Introduction & Getting started </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Basics Part 2 - Condition, Loop, Functions </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> PHP OOP - All you need </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> MYSQL Basics </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Final Part - PHP OOP & MYSQL CRUD </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text"> Laravel Introduction & Basics </h6>
                  </div>
                  <h6 class="lecture-count">
                    3 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Basics Part 1 - Introduction, Setup </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Basics Part 2 - MVC Architecture Practical Example </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Final Part - CRUD Application Project </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text">eCommerce Project Development</h6>
                  </div>
                  <h6 class="lecture-count">
                    12 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text">Introduction</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text">Introduction</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text">Introduction</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text"> Vue.js Basics, Vue Router & Vuex </h6>
                  </div>
                  <h6 class="lecture-count">
                    5 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Vue.js Introduction, CLI & Getting started </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Vue.js - Statement, List Rendering & Form Binding </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Vue Router - All you need </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Vuex - All you need </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Vue.js, Vue Router & Vuex - Combined Project </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text"> Vue.js & Laravel Project </h6>
                  </div>
                  <h6 class="lecture-count">
                    6 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Project Setup </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> REST API & Vue CRUD Part 1 </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> REST API & Vue CRUD Part 2 </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> REST API & Vue CRUD Part 3 </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Laravel REST API and Vue.js Authentication </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <font-awesome-icon :icon="['fas', 'chevron-right']"/>
                    <h6 class="text">Getting ready to serve</h6>
                  </div>
                  <h6 class="lecture-count">
                    4 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Domain & Hosting Class </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Fiverr & Upwork Freelancing </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Cloud server & Laravel Setup </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']"/>
                      <h6 class="text"> Portfolio Buildup & Developer CV Making </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- syllabus section end  -->
    <!-- Trainer section start -->
    <section class="trainer bg-light-gray">
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
                <h5>পার্থ দেবনাথ</h5>
                <p>সাপোর্ট</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Trainer section end -->
    <!-- FAQ section Start -->
    <section class="faq-area">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="trainer-title text-center">
              <h6> প্রশ্ন ও উত্তর </h6>
              <h4> আপনার প্রশ্ন আমাদের উত্তর </h4>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> একটি ব্যাচে কতজন ছাত্র/ছাত্রী নিবেন? </h5>
              <p> প্রত্যেক ব্যাচে ২৫ জন্য শিক্ষার্থী থাকবে । </p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> ক্লাস কখন নেওয়া হবে? </h5>
              <p> সকালে এবং সন্ধ্যায় ২ বেলায় ক্লাস হবে। আপনার যখন সুবিধা হবে, আপনার সুবিধা অনুযায়ী আপনি ক্লাসে
                জয়েন করতে পারবেন । </p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> আপনারা কোর্স শিখানোর পর, চাকরির গ্যারান্টি দিবেন? </h5>
              <p> আমরা কোন গ্যারান্টি দিচ্ছি না। তবে, এই মুহুর্তে আমরা প্রত্যেক ব্যাচ থেকে ২ জন শিক্ষার্থী কে
                ইন্টার্নশিপ এর সুবিধা দিচ্ছি। এছাড়াও আমরা চাকরি এবং ফ্রিল্যান্সিং এর ক্ষেত্রে সব রকমের
                সাহায্য করব। </p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> কোর্স শেষে কি সার্টিফিকেট দিবেন? </h5>
              <p> না। আপনি জানেন কি? আমাদের এই টেকনিক্যাল লাইনে, কেউ আপনার সার্টিফিকেট দেখবে না, দেখবে আপনার
                কাজ ও অভিজ্ঞতা। আর, এই দুইটা ক্ষেত্রেই আমরা আপনাকে গড়ে তুলব </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- FAQ section end -->
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
