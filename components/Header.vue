<template>
  <div class="bg-white">
    <!-- start header div for size pc -->

    <div
      class="container mr-10 hidden-xs-only hidden-sm-only"
      style="height:200px; width:auto"
    >
      <!-- start row -->
      <div class="row">
        <!-- start logo item -->
        <div class="col-6 mt-2">
          <nuxt-link to="/">
            <img
              src="../assets/image/logo.jpg"
              alt="logo"
              style="height: 110px; width:460px"
            />
            <p class="display-1 mr-12 text-dark">
              <span class="mr-12"></span>
              <span class="mr-12"></span>
              <span class="mr-7"></span>
              همه چی آموز
            </p>
          </nuxt-link>
        </div>
        <!-- end logo item -->

        <!-- start item two -->

        <div class="col-6 align-bottom mt-2">
          <nuxt-link to="">
            <img
              src="./../assets/image/Header/header-up1.gif"
              alt="tablighat"
              style="height:110px; width:620px"
            />
          </nuxt-link>
        </div>

        <!-- end item two -->

        <!-- end row -->
      </div>
    </div>

    <!-- end header div for size pc -->

    <!-- for size large -->
    <v-card
      color="grey lighten-4"
      class="hidden-xs-only hidden-sm-only"
      flat
      tile
      style="height:54px"
    >
      <v-toolbar dense>
        <v-toolbar-title>
          <span class="mr-10"></span>
          <span class="mr-10"></span>
          <span class="mr-10"></span>

          <!-- item one navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#">
                <span v-on="on" class="h-background">
                  نرم افزار
                  <span class="fas fa-angle-down"></span>
                </span>
              </a>
            </template>

            <v-list color="grey lighten-3" style="width:auto; height:auto">
              <!-- strat item one -->
              <nuxt-link to="/photoshop">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >فتوشاپ</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item one -->

              <!-- item two -->
              <nuxt-link to="/premiere">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >پریمیر</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item two -->

              <!-- item three -->
              <nuxt-link to="/motion_graphic">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >موشن گرافیک</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item three -->

              <!-- item four -->
              <nuxt-link to="illustrator">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >ایلوستریتور</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item four -->

              <!-- item five -->
              <nuxt-link to="/animation">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >انیمیشن</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item five -->
            </v-list>
          </v-menu>

          <!-- end item one navbar -->

          <!-- start item two navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  اینترنت
                  <span class="fas fa-angle-down"></span>
                </span>
              </a>
            </template>
            <v-list color="grey lighten-3" style="width:auto; height:auto">
              <nuxt-link to="/instagram">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش اینستاگرام</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>

              <!-- item two -->
              <nuxt-link to="telegram">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش تگلرام</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item two -->

              <!-- item three -->
              <nuxt-link to="/whatsapp">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش واتساپ</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item three -->

              <!-- item four -->
              <nuxt-link to="/twitter">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش توییتر</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end four three -->

              <!-- item five -->
              <nuxt-link to="facebook">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش فیسبوک</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item five -->

              <!-- item six -->
              <nuxt-link to="/youtube">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش یوتیوب</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item six -->

              <!-- item seven -->
              <nuxt-link to="/gmail">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آموزش جیمیل</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item seven -->
            </v-list>
          </v-menu>

          <!-- end item two navbar -->

          <!-- item three navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  موبایل
                  <span class="fas fa-angle-down"></span>
                </span>
              </a>
            </template>
            <v-list color="grey lighten-3" style="width:auto; height:auto">
              <nuxt-link to="/android">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >اندروید</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>

              <!-- item two -->
              <nuxt-link to="/iphone">
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item"
                    >آیفون و ios</v-list-item-title
                  >
                </v-list-item>
              </nuxt-link>
              <!-- end item two -->
            </v-list>
          </v-menu>

          <!-- end item three navbar -->

          <!-- start item four(computer) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  <nuxt-link to="/pc" style="color:#424242">کامپیوتر</nuxt-link>
                </span>
              </a>
            </template>
          </v-menu>

          <!-- end item four(computer) navbar -->

          <!-- start item five(learn other) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  <nuxt-link to="/otherLearn" style="color:#424242">
                    آموزش های دیگر
                  </nuxt-link>
                </span>
              </a>
            </template>
          </v-menu>

          <!-- end item five(learn other) navbar -->

          <!-- start item six(about) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  <nuxt-link to="/contactUs" style="color:#424242">
                    تماس با ما
                  </nuxt-link>
                </span>
              </a>
            </template>
          </v-menu>

          <!-- end item six(about) navbar -->

          <!-- start item seven(tablighat) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  <nuxt-link to="/tabligh" style="color:#424242">
                    تبلیغات
                  </nuxt-link>
                  <span class="fas fa-bullhorn text-success"></span>
                </span>
              </a>
            </template>
          </v-menu>

          <!-- end item seven(tablighat) navbar -->

          <!-- start item eight(shop) navbar -->

          <!-- <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-4">
                <span v-on="on" class="h-background">
                  فروشگاه
                  <span class="body-2 bg-danger white--text">حتما ببینید!</span>
                </span>
              </a>
            </template>
          </v-menu> -->
          <span style="margin-right:240px"></span>

          <!-- end item eight(shop) navbar -->

          <!-- start item nine(search) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-12">
                <span v-on="on" style="color:black">
                  <span class="fa fa-search"></span>
                </span>
              </a>
            </template>
            <v-list color="grey lighten-3" style="width:auto; height:auto">
              <nuxt-link to>
                <v-list-item>
                  <v-list-item-title class="font-weight-bold mr-2 h-item">
                    <b-form-input
                      placeholder="متن خود را وارد کنید"
                    ></b-form-input>
                  </v-list-item-title>
                </v-list-item>
              </nuxt-link>
            </v-list>
          </v-menu>

          <!-- end item nine(search) navbar -->

          <span></span>
          <!-- start item ten(shop) navbar -->

          <v-menu offset-y>
            <template v-slot:activator="{ on }">
              <a href="#" class="mr-10">
                <span v-on="on" style="color:black">
                  <nuxt-link to>
                    <v-btn icon color="green">
                      <span fab x-small color="green--text">
                        <span class="font-weight-bold">{{ counterCart }}</span>
                      </span>
                      <v-icon v-b-tooltip.hover title="مشاهده سبد "
                        >mdi-cart</v-icon
                      >
                    </v-btn>
                  </nuxt-link>
                </span>
              </a>
            </template>
          </v-menu>

          <!-- end item ten(shop) navbar -->
        </v-toolbar-title>
      </v-toolbar>
    </v-card>

    <!-- for size samll(phone) -->

    <v-card
      color="grey lighten-4"
      class="hidden-md-and-up"
      flat
      tile
      style="height:55px"
    >
      <v-toolbar dense>
        <v-app-bar-nav-icon v-b-toggle.sidebar-right></v-app-bar-nav-icon>

        <!-- <v-toolbar-title>Title</v-toolbar-title> -->

        <v-spacer></v-spacer>

        <!-- start logo size phone -->

        <nuxt-link to="/">
          <span class="text-dark title">همه چی آموز</span>
          <img
            src="./../assets/image/logo.jpg"
            alt="logo"
            style="height:45px; width:80px"
          />
        </nuxt-link>

        <!-- end logo size phone -->

        <!-- <v-btn icon color="green">
          <span fab x-small color="green--text">
            <span class="font-weight-bold">{{ counterCart }}</span>
          </span>
          <v-icon>mdi-cart</v-icon>
        </v-btn> -->
      </v-toolbar>

      <!-- start drap down -->

      <div>
        <b-sidebar id="sidebar-right" right shadow>
          <nuxt-link to="/">
            <h3 class="mr-4 text-dark">آموزش نرم افزار</h3>
          </nuxt-link>
          <hr />
          <div class="px-3 py-2 mr-2">
            <!-- start item one(app) -->

            <a href="#" class="mt-1" v-on:click="openItemApp = !openItemApp">
              <h4 style="color:black" class="h-background">
                نرم افزار
                <span class="mr-10"></span>
                <span class="fas fa-angle-down mr-10"></span>
              </h4>
            </a>
            <div class="border" v-if="openItemApp">
              <!-- start zir item one(photoshop) -->

              <div class="">
                <nuxt-link to="/photoshop">
                  <h5 class="mr-1 text-dark">
                    فتوشاپ
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item one(photoshop) -->

              <!-- start zir item two(پریمیر) -->

              <div class="" v-if="openItemApp">
                <nuxt-link to="/premiere">
                  <h5 class="mr-1 text-dark">
                    پریمیر
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item two(پریمیر) -->

              <!-- start zir item three(corel) -->

              <div class="" v-if="openItemApp">
                <nuxt-link to="/motion_graphic">
                  <h5 class="mr-1 text-dark">
                    موشن گرافیک
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item three(corel) -->

              <!-- start zir item four(gimp) -->

              <div class="" v-if="openItemApp">
                <nuxt-link to="/illustrator">
                  <h5 class="mr-1 text-dark">
                    ایلوستریتور
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item four(gimp) -->

              <!-- start zir item five(inkskip) -->

              <div class="my-2" v-if="openItemApp">
                <nuxt-link to="/animation">
                  <h5 class="mr-1 text-dark">
                    انیمیشن
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item five(inkskip) -->
            </div>

            <!-- end item one(app) -->

            <!-- start item two(network) -->

            <a
              href="#"
              class="mt-2"
              v-on:click="openItemNetwork = !openItemNetwork"
            >
              <h4 style="color:black" class="h-background">
                اینترنت
                <span class="mr-10"></span>
                <span class="mr-2"></span>
                <span class="fas fa-angle-down mr-10"></span>
              </h4>
            </a>

            <div class="border" v-if="openItemNetwork">
              <!-- start zir item one(Learn Instagram) -->

              <div class="">
                <nuxt-link to="/instagram">
                  <h5 class="mr-1 text-dark">
                    آموزش اینستاگرام
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item one(learn instagram) -->

              <!-- start zir item two(learn telegram) -->

              <div class="">
                <nuxt-link to="/telegram">
                  <h5 class="mr-1 text-dark">
                    آموزش تلگرام
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item two(learn telegram) -->

              <!-- start zir item three(learn whatsapp) -->

              <div class="">
                <nuxt-link to="/whatsapp">
                  <h5 class="mr-1 text-dark">
                    آموزش واتساپ
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item three(learn whatsapp) -->

              <!-- start zir item four(learn twitter) -->

              <div class="">
                <nuxt-link to="/twitter">
                  <h5 class="mr-1 text-dark">
                    آموزش توییتر
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item four(learn twitter) -->

              <!-- start zir item five(learn facebook) -->

              <div class="">
                <nuxt-link to="facebook">
                  <h5 class="mr-1 text-dark">
                    آموزش فیسبوک
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item five(learn facebook) -->

              <!-- start zir item six(learn youtube) -->

              <div class="">
                <nuxt-link to="/youtube">
                  <h5 class="mr-1 text-dark">
                    آموزش یوتیوب
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item six(learn youtube) -->

              <!-- start zir item seven(learn gmail) -->

              <div class="">
                <nuxt-link to="/gmail">
                  <h5 class="mr-1 text-dark">
                    آموزش جیمیل
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item seven(learn gmail) -->
            </div>

            <!-- end item two(network) -->

            <!-- start item three(phone) -->

            <a
              href="#"
              class="mt-1"
              v-on:click="openItemPhone = !openItemPhone"
            >
              <h4 style="color:black" class="h-background">
                موبایل
                <span class="mr-10"></span>
                <span class="mr-4"></span>
                <span class="fas fa-angle-down mr-10"></span>
              </h4>
            </a>

            <div class="border" v-if="openItemPhone">
              <!-- start zir item one(Learn Instagram) -->

              <div class="">
                <nuxt-link to="/android">
                  <h5 class="mr-1 text-dark">
                    اندروید
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item one(learn instagram) -->

              <!-- start zir item two(Learn Instagram) -->

              <div class="">
                <nuxt-link to="/iphone">
                  <h5 class="mr-1 text-dark">
                    آیفون و ios
                  </h5>
                </nuxt-link>
              </div>

              <!-- end zir item two(learn instagram) -->
            </div>
            <!-- end item htree(phone) -->

            <!-- start item four(pc) -->

            <nuxt-link to="/pc" class="mt-1">
              <h4 style="color:black" class="h-background">
                کامپیوتر
              </h4>
            </nuxt-link>

            <!-- end item four(pc) -->

            <!-- start item five(learn other) -->

            <nuxt-link to="/otherLearn" class="mt-1">
              <h4 style="color:black" class="h-background">
                آموزش های دیگر
              </h4>
            </nuxt-link>

            <!-- end item five(learn other) -->

            <!-- start item six(about) -->

            <nuxt-link to="/contactUs" class="mt-1">
              <h4 style="color:black" class="h-background">
                تماس با ما
              </h4>
            </nuxt-link>

            <!-- end item six(about) -->

            <!-- start item seven(tablighat) -->

            <nuxt-link to="/tabligh" class="mt-1">
              <h4 style="color:black" class="h-background">
                تبلیغات
                <span class="fas fa-bullhorn text-success"></span>
              </h4>
            </nuxt-link>

            <!-- end item seven(tablighat) -->

            <!-- start item eight(shop) -->

            <!-- <nuxt-link to="" class="mt-1">
              <h4 style="color:black" class="h-background">
                فروشگاه
                <span class="body-2 bg-danger white--text">حتما ببینید!</span>
              </h4>
            </nuxt-link> -->

            <!-- end item eight(shop) -->
          </div>
        </b-sidebar>
      </div>

      <!-- end drap down -->
    </v-card>

    <!-- End for size samll(phone) -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      counterCart: 0,
      openItemApp: false,
      openItemNetwork: false,
      openItemPhone: false
    };
  }
};
</script>

<style scoped>
/* .size-font-nav {
  font-size: 14px;
} */

.h-background {
  color: #424242;
  font-size: 18px;
}

.h-background:hover {
  background-color: #eeeeee;
}
.h-item {
  transition: 0.5s;
  font-size: 15px;
}

.h-item:hover {
  font-size: 20px;
  transition-delay: 1000;
  color: black;
}
</style>
