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
                সঠিক ভাবে কোর্স সম্পূর্ণ করার পর, প্রত্যেক ব্যাচ থেকে আমরা ২ জন ছাত্র/ছাত্রী কে ইন্টার্নশিপ সুবিধা প্রদান
                করব ।
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
                HTML, CSS, JavaScript, Git, VSCode, Bootstrap</b> এর যাবতীয় চিটশিট প্রদান করা হবে। যা কোর্স চলাকালীন সময়ে
                শিক্ষার্থীদের সহায়ক হবে।
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
                ফ্রিল্যান্সিং সম্পর্কে ফ্রিল্যান্সারদের থেকে সেরা গাইডলাইন আর কেও দিতে পারবে না। আমাদের প্রশিক্ষকদের রয়েছে
                ফ্রিল্যান্সিং এর অভিজ্ঞতা ।
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
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
