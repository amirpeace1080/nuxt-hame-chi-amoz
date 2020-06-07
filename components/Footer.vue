<template>
  <v-footer>
    <v-card flat tile class="dark--text text-center">
      <v-card-text>
        <!-- one item masenger -->
        <v-tooltip bottom>
          <template v-slot:activator="{ on }">
            <a href="https://telegram.me/peace1080">
              <v-icon color="primary" dark v-on="on" size="26px" class="mx-4">mdi-telegram</v-icon>
            </a>
          </template>
          <span>تلگرام</span>
        </v-tooltip>
        <!-- end item masenger -->

        <!-- one item masenger -->
        <v-tooltip bottom>
          <template v-slot:activator="{ on }">
            <a href="#">
              <v-icon color="primary" dark v-on="on" size="26px" class="mx-4">mdi-whatsapp</v-icon>
            </a>
          </template>
          <span>واتساپ</span>
        </v-tooltip>
        <!-- end item masenger -->

        <!-- one item masenger -->
        <v-tooltip bottom>
          <template v-slot:activator="{ on }">
            <a href="https://www.instagram.com/peace_1080">
              <v-icon color="primary" dark v-on="on" size="26px" class="mx-4">mdi-instagram</v-icon>
            </a>
          </template>
          <span>اینستاگرام</span>
        </v-tooltip>
        <!-- end item masenger -->

        <!-- one item masenger -->
        <v-tooltip bottom>
          <template v-slot:activator="{ on }">
            <a href="https://www.linkedin.com/in/mohammad-sharifi-b8364b194">
              <v-icon color="primary" dark v-on="on" size="26px" class="mx-4">mdi-linkedin</v-icon>
            </a>
          </template>
          <span>لینکدین</span>
        </v-tooltip>
        <!-- end item masenger -->

        <!-- <v-btn v-for="icon in icons" :key="icon" class="mx-4 dark--text" icon>
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>-->
      </v-card-text>

      <v-card-text class="dark--text pt-0 text-right mr-3">
        <h2 size="66">شرکت...</h2>

        <p
          class="mt-3 ml-2 mr-3"
        >فعالیت خود را از سال 1393, به عنوان بزرگترین ارائه دهنده ابزار و نرم افزارهای امنیت اطلاعات رایانه ای آغاز نموده است وبا اخذ نمایندگی رسمی شرکت های ESET و Kaspersky سبد متنوعی از آنتی ویروس های خانگی و تحت شبکه را در اختیار گرفته تا یک محصول اورجینال به کاربران خود ارائه ده. این شرکت با دارا بودن دفاتر نمایندگی در سراسر کشور و با تشکیل تیم فنی قدرتمند برای پشتیبانی همواره تلاش داشته تا بهترین راهکارها را در قالب محصولات و خدمات در اختیار مشتریان قرار دهد. همچنین این شرکت با اجرای بهترین خدمات از جمله طراحی سایت , نرم افزار مدیریت ارتباط با مشریان, تولید ویدیورهای آموزشی توانسته مشاوری برای بروز بودن کسب و کار مشتریان خود باشد و با شعار "کسب و کار شما گران بها است" تا فرداهایی روشن تر همواره برای خدمت رسانی به هموطنان عزیز در تلاش بوده است.</p>
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="dark--text">
        <strong>2020-05-04</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"]
  })
};
</script>

<style scoped>
a {
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}
</style>