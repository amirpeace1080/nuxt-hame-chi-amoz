<template>
  <div class="container color-all">
    <p class="mr-2" style="font-size:20px">آموزش پریمیر ۲۰۲۰</p>
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
              <span> 20 نفر</span>
            </p>
            <p>
              <span class="fas fa-layer-group"></span>
              <span class="color-title"> سطح دوره :</span>
              <span> مبتدی</span>
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
                src="https://cdn4.iconfinder.com/data/icons/adobe-apps/512/Premiere_pro-512.png"
                alt="premiere"
                style="height:440px; width:90%"
              />
            </div>
            <!-- end image -->

            <!-- start title  -->
            <br /> 
            <nuxt-link to="/premiere">
              <p class="text-title">آموزش پریمیر ( Premiere )</p>
            </nuxt-link>
            <!-- end title -->

            <!-- start description -->
            <div>
              <br />
              <p>آموزش Premiere 2020</p>
              <br />
              <p>
                در این دوره قصد داریم تا با زبان ساده و روان هر چه راحت تر شما
                رو با نرم افزار پریمیر اشنا کنیم تا اماده بشید برای دوره حرفه ای
                این نرم افزار همچنین این اموزش به صورت کاملا رایگان در اختیار
                شما علاقه مندان عزیز قرار گرفته.
              </p>
              <p>
                نرم افزار پریمیر یکی از بهترین نرم افزار ها برای تدوین و کارهای
                ویدیویی که دریچه ورود شما به دنیایی تدوین یا اصلاح ویدیو ها و
                جلوه های ویژه و ... میباشد.
              </p>
              <p>
                اگر شما در برنامه ریزی خود قصد یادگیری افتر افکت و جلوه های ویژه
                و بسیاری از تکنیک های پر کاربرد در دنیایه تدوین و ساخت انواع
                ویدیو ها را دارید پیش نیاز شما دانش ابتدایی با این نرم افزار
                میباشد.
              </p>
              <p>
                از این نرم افزار در فیلم های هالیوودی و... استفاده زیادی میشود .
              </p>
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
      title: "همه چی آموز - پریمیر"
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
