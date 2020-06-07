<template>
  <div class="container color-all">
    <p class="mr-2" style="font-size:20px">آموزش موشن گرافیک </p>
    <div class="container--fluid">
      <div class="row">
        <!-- start about teacher !-->
        <div
          class="col-lg-4 col-sm-12 border ml-3 mr-3 mt-2 bg-white"
          style="height:400px"
        >
          <div class="container">
            <i class="fas fa-dollar-sign fa-lg" style="color:#00E676"></i>
            <span> قیمت این دوره: </span>
            <span class="headline" style="color:#00E676"> رایگان </span>
            <hr />
            <p>
              <i class="fas fa-user"></i>
              <span class="color-title"> مدرس این دوره: </span>
              <span> ... </span>
            </p>
            <p>
              <i class="fas fa-user-friends"></i>
              <span class="color-title"> تعداد دانشجویان این دوره: </span>
              <span> ۸ نفر</span>
            </p>
            <p>
              <span class="fas fa-layer-group"></span>
              <span class="color-title"> سطح دوره :</span>
              <span> متوسط</span>
            </p>
            <p>
              <span class="fas fa-info-circle"></span>
              <span class="color-title">وضعیت دوره :</span>
              <span class="text-info"> به اتمام رسیده</span>
            </p>
            <p>
              <span class="fas fa-calendar-check"></span>
              <span class="color-title"> تاریخ ثبت دوره‌: </span>
              <span> ۱۳۹۹/۰۲/۱۸</span>
            </p>
            <p>
              <span class="fas fa-calendar-alt"></span>
              <span class="color-title"> تاریخ آخرین بروزرسانی: </span>
              <span> ۱۳۹۹/۰۳/۱۰</span>
            </p>
          </div>
        </div>

        <!-- end about teacher !-->

        <!-- start content photoshop !-->
        <div class="col-lg-7 col-sm-12 border mr-3 ml-3 mt-2 bg-white">
          <div class="container ">
            <!-- start image -->
            <div class="text-left">
              <img
                src="data:image/jpeg;base64,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"
                alt="premiere"
                style="height:440px; width:90%"
              />
            </div>
            <!-- end image -->

            <!-- start title  -->
            <br />
            <nuxt-link to="/premiere">
              <p class="text-title">آموزش موشن گرافیک</p>
            </nuxt-link>
            <!-- end title -->

            <!-- start description -->
            <div>
              <br />
              <p>سلام خدمت دوستان عزیز</p>
              <p>امیدوارم حالتون خوب باشه</p>
              <p>
                توی این متن میخام دوره موشن گرافیک (ویژه بازار کار) رو بهتون
                معرفی کنم.
              </p>
              <p>
                اگه تا حالا دقت کرده باشید، توی اغلب اوقات کشور های دیگه توی
                زمینه های دیجیتال از ما جلو ترن، وتوی موشن گرافیک هم با اینکه ما
                موشن گرافیست های عالی توی کشور داریم، اما سطح کلی موشن ما پایین
                تر از اون هاس
              </p>
              <p>
                برا همین من تصمیم گرفتم این اختلاف رو بررسی کنم، تا شاید ما هم
                بتونیم مثل اونا کار کنیم، تو این مسیر من با دوره های موشن گرافیک
                درخشانی توی سطح بین الملل اشنا شدم، که بسیار کم یابند و قیمت
                مجموع اونا ها به بیش از 1500 دلار می رسه که شما رو به یه غول
                موشن گرافیک تبدیل می کنه،
              </p>
              <p>
                چون ممکنه شما در طول دوره گیج بشین، من خودم دوره ای رو قبل از
                اون تدوین کردم که شامل تمام نکات مورد نیاز موشن گرافیک میشه، و
                به عنوان مکمل،اون دوره هارو براتون قرار دادم
              </p>
              <p>
                که دموی کوچکی و نمونه کار های خیلی کمی که با این دوره ها ساخته
                شده رو براتون توی ویدیو معرفی دوره قرار دادم، این دوره ها بسیار
                قدرتمند اند و شما رو تا سطح یک موشن گرافیست با استاندارد های بین
                المللی می رسونه، از همه مهم تر بعد دوره می تونید درخواست مدرک
                معتبر دانشگاه ازاد بدید و یه جای خوب با مهارت کافی استخدام بشین
              </p>
              <p>دقت کنین این دوره رایگانه، اون مبلغ ناچیز هم برا مدرکه</p>
              <p>امیدوارم موفق باشید 😉</p>
            </div>
            <!-- end description -->
          </div>
        </div>

        <!-- end content photoshop !-->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  head() {
    return {
      title: "همه چی آموز - موشن گرافی"
    };
  }
};
</script>

<style scoped>
.color-all {
  color: #212121;
  font-size: 14px;
}

.color-title {
  color: #757575;
}

.text-title {
  color: rgb(34, 34, 34);
  font-size: 18px;
  font-weight: bold;
}
</style>
