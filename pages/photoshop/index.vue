<template>
  <div class="container color-all">
    <p class="mr-2" style="font-size:20px">آموزش فتوشاپ ( Photoshop )</p>
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
              <span> 4 نفر</span>
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
                src="data:image/png;base64,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"
                alt="premiere"
                style="height:440px; width:90%"
              />
            </div>
            <!-- end image -->

            <!-- start title  -->
            <br />
            <nuxt-link to="/photoshop">
              <p class="text-title">آموزش فتوشاپ ( Photoshop )</p>
            </nuxt-link>
            <!-- end title -->

            <!-- start description -->
            <div>
              <br />
              <p>آموزش رایگان Photoshop از مقدماتی تا پیشرفته</p>
              <br />
              <br />
              <p>در این دوره به صورت کامل با نرم افزار فتوشاپ آشنا خواهید شد</p>
              <p>
                این دوره پیش نیاز تمامی دوره های حرفه ای هستش که در آینده
                میخواهید اونارو ببینید.
              </p>
              <br />
              <br />
              <p>سرفصل ها:</p>
              <p>دانلود،خارج کردن از حالت فشرده،نصب مقدماتی</p>
              <p>
                مباحث پایه گرافیک Vector – Raster – Resolution – Color mode
                مقدماتي
              </p>
              <p>
                آشنایی با محیط، تنظیمات صفحه و استفاده از ابزار ترسیم پایه Corel
                work space - Rectangle tool – Ellipse tool مقدماتي
              </p>
              <br />
              <p>
                روشهای انتخاب و جابجایی و کپی کردن و حذف اشکال Select object,
                Move , How to copy , Duplicate, clone, Delete.
              </p>
              <p>
                روشهای انتخاب و جابجایی و کپی کردن و حذف اشکال Select object,
                Move , How to copy , Duplicate, clone, Delete.
              </p>
              <p>
                ادامه ابزار های ترسیم پایه Polygon –Star – Complex star – Graph
                paper – basic shapes ,…. مقدماتي
              </p>
              <p>
                Text Box: فرامین ترکیبی Weld – Trim – Intersect – Simplify –
                Combine- Group – Ungroup – Ungroup All متوسط
              </p>
              <p>
                خطوط راهنما و زوم Zoom tool – Grid – Guide line – Dynamic guide
                -Snap ( All of snaps) مقدماتي
              </p>
              <p>
                نگ کردن داخل اشکال و رنگ و ضخامت وتنظيمات خطوط Uniform fill -
                Outline مقدماتي
              </p>
              <p>کاربرد و اجرای دستور powerclip و تنظیمات Powerclip متوسط</p>
              <p>
                ابزارهای ترسیم خط Freehand – Bezier – pen tool – Artistic media
                –B spline … متوسط
              </p>
              <p>کنترل فرم و گره های خطوط Shape tool متوسط و پيشرفته</p>
              <p>
                پر کردن اشکال از رنگ ، رنگهای طیفی ، بافتها و... Fill tools
                –interactive fill toll- Mesh tool متوسط و پيشرفته
              </p>
              <p>
                متن و مدیریت متن-نوشتن متن روی مسیر – تبدیل متن به شکل Text tool
                –Type on path- Convert text to curve متوسط و پيشرفته
              </p>
              <p>
                ابزارهای کمک ویرایشی Knife – Eraser – Crop – Smudge – Roughen -
                Virtual Segment – smart fill متوسط و پيشرفته
              </p>
              <p>
                ابزارهای خطوط متصل کننده و ابزارهای اندازه گیری طول و زاویه
                Connector tools – Dimension tools متوسط و پيشرفته
              </p>
              <p>
                دستورات Import و Export Export – Import - File extension( TIff
                –JPEG – PSD- PDF- EPS- AI – CDR) متوسط
              </p>
              <p>
                بررسی دستورات لازم و سودمند منوی Bitmap Convert to bitmap –
                Trace – Filters متوسط و پيشرفته
              </p>
              <p>ابزار و منوی جدول Table tool – Table menu متوسط و پيشرفته</p>
              <p>
                مدیریت صفحات و بررسی منوی Layout و پنل Object manager Pages –
                Layout menu – Object manager – Master Pages متوسط و پيشرفته
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
      title: "همه چی آموز - فتوشاپ"
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
