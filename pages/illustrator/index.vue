<template>
  <div class="container color-all">
    <p class="mr-2" style="font-size:20px">آموزش ایلوستریتور</p>
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
              <span> ۲۲۱ نفر</span>
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
                src="https://faradars.org/wp-content/uploads/2016/04/fvill9408-svg.svg"
                alt="premiere"
                style="height:440px; width:90%"
              />
            </div>
            <!-- end image -->

            <!-- start title  -->
            <br />
            <nuxt-link to="/premiere">
              <p class="text-title">آموزش نرم افزار Adobe illustrator</p>
            </nuxt-link>
            <!-- end title -->

            <!-- start description -->
            <div>
              <br />
              <p>
                آموزش یکی از معروف ترین و کاربردی ترین نرم افزار های شرکت Adobe
                به نام ایلوستریتور. که از این نرم افزار می توان به عنوان طراحی
                لوگو،طراحی واسط کاربری ui ،نقشه کشی و... استفاده کرد.که در این
                دوره تمام مطالب فوق به صورت کامل توضیح داده خواهد شد.
              </p>
              <p>
                شما پس از گزراندن این دوره مطالب مقدماتی را فرا گرفته اید به غیر
                از این مقداری هم از نرم افزار فوتو شاپ رو یاد خواهید گرفت. مادر
                این دوره،طراحی لوگوی های بعضی از شرکت ها را طراحی خواهیم کرد
                مثلا:لوگوی اینستاگرام،
              </p>
              <p>
                گوی تلگرام،لوگوی وب سایت تاپلرن و... درضمن ما دراین دوره طراحی
                واسط کاربری ui رو هم خواهیم داشت. مثلا ما صفحه اول وب سایت تاپ
                لرن رو در نرم افزار ایلوستریتور طراحی خواهیم کرد. در این دوره به
                صورت کاملا جزئی نقشه کشی هم درس داده میشود (چون از نرم افزار
                اتوکد قدر تمند وارد این عرصه شده است.)
              </p>
              <p>مواردی که در این دوره آموزش داده می شود:</p>
              <p>1. طراحی آیکون</p>
              <p>2. طراحی شمسه</p>
              <p>3. طراحی لوگو</p>
              <p>4. طراحی ui</p>
              <p>5. نقشه کشی</p>
              <p>6. ...</p>
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
      title: "همه چی آموز - ایلوستریتور"
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
