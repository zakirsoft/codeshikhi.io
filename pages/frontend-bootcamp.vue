<template>
  <div>
    <!-- banner section start  -->
    <section class="subbanner bg-light-gray">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-8">
            <div class="subbanner__content">
              <div class="btn-xs bg-color d-inline-block btn-pill text-uppercase mb-2"><b>Trending</b></div>
              <h1 class="subbanner__header"> মাস্টারিং ফ্রন্টএন্ড ডেভেলপার বুটক্যাম্প </h1>
              <p class="subbanner__pra mb-3">
                আমাদের ক্লাস গুলো সাধারন শিক্ষার্থীদের কথা ভেবেই সাজানো হয়েছে মূলত। তাই প্রিয় শিক্ষার্থীদের চিন্তার কোনো
                কারণ নেই। আমারা আমাদের শিক্ষার্থীদের যুগ-উপোযোগী প্রশিক্ষণ প্রধান এর মাধ্যম্যে দক্ষ করে তুলতে দীর্ঘ
                প্রতিজ্ঞা পূর্ন।
                এখানে প্রিয় শিক্ষার্থীদের দেখানো হবে কি করে একটি স্ট্যাটিক ওয়েব সাইট তৈরি করা হয় - <code><b>HTML CSS
                    BOOTSTRAP javaScript Jquery</b></code> এর মাধ্যম্যে। ক্লাস সম্পূর্ণ করার পর আমরা আমদের প্রিয়
                শিক্ষার্থীদের সর্বাত্মক সহযোগিতা করবো লোকাল জব ও ফ্রিল্যান্সিং এ ক্যারিয়ার গড়ে তুলতে।
              </p>
              <div class="d-flex align-items-center flex-wrap">
                <!-- Authors -->
                <div class="d-flex align-items-center mr-4">
                  <div class="avatar-group">
                    <span class="avatar avatar-xs avatar-circle">
                      <img class="avatar-img" src="~/assets/images/team/Rashed.jpg" alt="Image Description">
                    </span>
                  </div>
                  <span class="pl-2"> Created by <a class="link-underline ml-1" target="_blank" href="#"> Sheikh Rashed
                    </a></span>
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
            <span class="text-uppercase d-inline-block mb-2">বৈশিষ্ট্য সমূহ</span>
            <h2>বুটক্যাম্পে আপনি যা পাচ্ছেন</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-5 col-md-6 col-sm-12 mb-5">
            <div class="mb-5">
              <div class="icon-box mt-3">
                <font-awesome-icon :icon="['fas', 'user']" />
              </div>
              <h3>কোর্স চলাকালীন</h3>
            </div>
            <ul class="check-list">
              <li>
                <font-awesome-icon :icon="['fas', 'check']" />
                <p> <b>২৪/৭</b> সাপোর্ট কোর্স চলাকালীন </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']" />
                <p><b>৬+</b> টির ও বেশী প্রজেক্ট থাকছে </p>
              </li>
              <li>
                <font-awesome-icon :icon="['fas', 'check']" />
                <p><b>প্রশ্নাত্তর পর্ব</b> প্রতি ক্লাস শেষে</p>
              </li>
            </ul>
          </div>
          <div class="col-lg-7 col-md-6 col-sm-12">
            <div class="position-relative">
              <div class="bootcamp-block bootcamp-skew__30 featurescard">
                <div class="header">
                  <div class="title">
                    <div class="icon">
                      <font-awesome-icon :icon="['fas', 'code']" />
                    </div>
                    <p>ফ্রন্টএন্ড বুটক্যাম্প </p>
                  </div>
                  <p>
                    আধুনিক প্রযুক্তির সমন্বয়ে ফ্রন্টএন্ড ডেভেলপমেন্ট কোর্সটি সাজানো হয়েছে,যেখানে কোর্সটি সম্পন্ন করার
                    পর, যেকোন শিক্ষার্থী যেকোন স্ট্যাটিক ওয়েবসাইট ডেভেলপ করতে সক্ষম হয়ে উঠবে। তাছাড়াও থাকছে লোকাল জব ও
                    ফ্রিল্যান্সিং ক্যারিয়ারের উপর বিশেষ গাইডলাইন, যা আমরা মনে করি - <b>প্রিয় শিক্ষার্থীদের</b> সামনের
                    দীর্ঘ পথ গুলোয় আগিয়ে যাওয়ার জন্য যে সিদ্ধান্তের প্রয়োজন হবে তা নিতে সহজ হয়ে উঠবে।
                  </p>
                </div>
                <div class="body">
                  <!-- <p class="headline"> আপনি যা যা শিখবেন </p> -->
                  <ul class="check-list">
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> HTML </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p> CSS </p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>JavaScript</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>Bootstrap</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>SCSS</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>React & Vue.js</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>Git & Github</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>Upwork Guidline</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>Fiverr Guidline</p>
                    </li>
                    <li>
                      <font-awesome-icon :icon="['fas', 'check']" />
                      <p>Resume Building</p>
                    </li>
                  </ul>
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
              <div class="section_brief"> আমাদের চমৎকার কিছু কার্যক্রম শুধু মাত্র কোর্সে ভর্তি হয়ে আপনিও পেতে পারেন </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'user']" />
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
                <font-awesome-icon :icon="['fas', 'graduation-cap']" />
              </span>
              <h6 class="go_title">
                ইন্টার্নশিপ সুবিধা
              </h6>
              <div class="go_brief">
                সঠিক ভাবে কোর্স সম্পূর্ণ করার পর, প্রত্যেক ব্যাচ থেকে আমরা ২ জন ছাত্র/ছাত্রী কে ইন্টার্নশিপ সুবিধা প্রদান
                করব ।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'globe']" />
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
                <font-awesome-icon :icon="['fas', 'list']" />
              </span>
              <h6 class="go_title">
                বিনামুল্যে চিটশিট
              </h6>
              <div class="go_brief">
                HTML, CSS, JavaScript, Git, VSCode, Bootstrap</b> এর যাবতীয় চিটশিট প্রদান করা হবে। যা কোর্স চলাকালীন সময়ে
                শিক্ষার্থীদের সহায়ক হবে।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'dollar-sign']" />
              </span>
              <h6 class="go_title">
                ফ্রিল্যান্সিং গাইডলাইন
              </h6>
              <div class="go_brief">
                ফ্রিল্যান্সিং সম্পর্কে ফ্রিল্যান্সারদের থেকে সেরা গাইডলাইন আর কেও দিতে পারবে না। আমাদের প্রশিক্ষকদের রয়েছে
                ফ্রিল্যান্সিং এর অভিজ্ঞতা ।
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="go__box-content">
              <span class="go_icon">
                <font-awesome-icon :icon="['fas', 'briefcase']" />
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
    <section class="syllabus" id="previewSyllabus">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="trainer-title text-center">
              <h6> সিলেবাস </h6>
              <h4> তিন মাস ব্যাপী কোর্স প্লান</h4>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-md-5">
            <div class="mb-5">
              <h3>
                <!-- ফ্রন্টএন্ড ডেভেলপার হওয়ার জন্য যা যা প্রয়োজন সেই সব নিয়ে আমাদের এই সিলেবাস । -->
                সংক্ষিপ্ত সিলেবাস
              </h3>
              <p>
                <!-- আমাদের সপ্তাহে ৩দিন ক্লাস হবে -->
                সপ্তাহে ৩দিন <b>রবি, মঙ্গল ও বৃহস্পতিবার</b> আমাদের ক্লাস এর কার্যক্রম হবে, প্রতি ক্লাস এর সময়সীমা থাকবে
                <b>2 ঘন্টা</b> ।
                <br>
                ক্লাস এর সময়ঃ <b>বিকাল ( ৩.০০ টা - ৫.০০ টা )</b>
              </p>
            </div>
            <div class="row">
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> ৩৬ </h4>
                  <p><b>সর্বমোট ক্লাস </b></p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> ৭২ </h4>
                  <p><b>সর্বমোট ঘন্টা</b> </p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> ৬+ </h4>
                  <p><b>সর্বমোট প্রজেক্ট </b></p>
                </div>
              </div>
              <div class="col-md-6 col-6">
                <div class="mb-5">
                  <h4> ২৫ </h4>
                  <p><b>প্রতি ব্যাচে</b> </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-7">
            <div class="syllabus-data">
              <div class="toggle active">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">HTML- Hyper Text Markup Language</h6>
                  </div>
                  <h6 class="lecture-count">
                    6 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Welcome - Introduction of Html, Environment Setup</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Basic Tags & Their Attributes</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Html Basic & nested Tables</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Html Forms</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Semantic Tags </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Section-End Final Project & Overview of HTML</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">&nbsp;CSS - Cascading Style Sheets</h6>
                  </div>
                  <h6 class="lecture-count">
                    8 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;Welcome - Introduction of CSS, Environment Setup</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Units & Spacing</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Display, Backgrounds & Pseudo (classes,Elements)</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Positions </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Flexbox </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Animations </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">&nbsp;CSS - Media Query </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Section-End Final Project & Overview of CSS </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text"> JavaScript & Jquery </h6>
                  </div>
                  <h6 class="lecture-count">
                    8 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Welcome - Introduction of JavaScript & Jquery, Environment Setup </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> JavaScript Variable & DataTypes
                      </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Logical Operators & Expression </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Conditional Statements & objects </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Functions </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> DOM - Document Object Model</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Jquery & Plugins</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Section-End Final Project & Overview of javaScript </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text"> Bootstrap </h6>
                  </div>
                  <h6 class="lecture-count">
                    4 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Welcome - Introduction of Bootstrap, Environment Setup </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Bootstrap Components Customizations & Uses</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Bootstrap Grid Layout
                      </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> REST API & Vue CRUD Part 3 </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">Projects</h6>
                  </div>
                  <h6 class="lecture-count">
                    4 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Psd to html</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> XD to html </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> figma to html </h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> Build Portfolio Site</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">Git & Github</h6>
                  </div>
                  <h6 class="lecture-count">
                    1 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text"> git & github Configuration</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">Market Places</h6>
                  </div>
                  <h6 class="lecture-count">
                    2 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Fiverr Market Place</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Upwork Market Place</h6>
                    </div>
                    <p class="count"> 2hrs </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">Resume Building</h6>
                  </div>
                  <h6 class="lecture-count">
                    1 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">
                        Prepare Your Resume For local Markets
                      </h6>
                    </div>
                    <p class="count">
                      2hrs
                    </p>
                  </div>
                </div>
              </div>

              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">React & Vue</h6>
                  </div>
                  <h6 class="lecture-count">
                    1 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Which Front End Framework will be suitable for you</h6>
                    </div>
                    <p class="count">
                      2hrs
                    </p>
                  </div>
                </div>
              </div>
              <div class="toggle">
                <div class="header bg-light-gray">
                  <div class="icon-group">
                    <i class="fas fa-chevron-right down-arrow"></i>
                    <h6 class="text">Php & Sql</h6>
                  </div>
                  <h6 class="lecture-count">
                    1 Lectures
                  </h6>
                </div>
                <div class="content">
                  <div class="class">
                    <div class="icon-group">
                      <font-awesome-icon :icon="['fas', 'play-circle']" />
                      <h6 class="text">Php Crash Introduction</h6>
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
    <Team />
    <!-- FAQ section Start -->
    <section class="faq-area">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="trainer-title text-center">
              <h6> প্রশ্ন-উত্তর </h6>
              <h4> আপনার প্রশ্ন আমাদের উত্তর </h4>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> প্রতি ব্যাচ এ শিক্ষার্থী সংখ্যা কত হবে ? </h5>
              <p> আমাদের প্রতি ব্যাচে শিক্ষার্থী সংখ্যা সর্বোচ্চ ২৫ জন করে থাকবে ।</p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> ক্লাস কখন নেওয়া হবে? </h5>
              <p> আপাদও আমাদের বিকাল এর ব্যাচের কার্যক্রম চলমান থাকবে, যা শুরু হবে বিকালঃ<b> ৩.০০ টা - ৫.০০ টা </b>
                পর্যন্ত। সপ্তাহে ৩ দিন - রবি , মঙ্গল ও বৃহস্পতিবার । </p>

            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> আপনারা কোর্স শিখানোর পর, চাকরির গ্যারান্টি দিবেন? </h5>
              <p>
                <!-- আমরা কোন গ্যারান্টি দিচ্ছি না। তবে, এই মুহুর্তে আমরা প্রত্যেক ব্যাচ থেকে ২ জন শিক্ষার্থী কে ইন্টার্নশিপ এর সুবিধা দিচ্ছি। এছাড়াও আমরা চাকরি এবং ফ্রিল্যান্সিং এর ক্ষেত্রে সব রকমের সাহায্য করব।  -->
                গ্যারান্টি দিচ্ছি না , তবে সুযোগ দিবো আমাদের সাথে ইন্টার্নশিপ করার জন্য, যারা ভালো পারফরমেন্স করবে।
              </p>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="faq-area__text">
              <h5> কোর্স শেষে কি সার্টিফিকেট দিবেন? </h5>
              <p>
                <!-- না। আপনি জানেন কি? আমাদের এই টেকনিক্যাল লাইনে, কেউ আপনার সার্টিফিকেট দেখবে না, দেখবে আপনার কাজ ও অভিজ্ঞতা। আর, এই দুইটা ক্ষেত্রেই আমরা আপনাকে গড়ে তুলব -->
                আমরা কোনো প্রকার সার্টিফিকেট দিবো না আমাদের বুটক্যাম্প থেকে । আমরা দক্ষতা নীতিতে বিশ্বাসি, যেখানে আপনার
                কাজ আপনাকে মূল্যায়ন করবে , সেখানে সার্টিফিকেটের এর কোনো প্রয়োজন নেই ।
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- FAQ section end -->
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

<style>

</style>
