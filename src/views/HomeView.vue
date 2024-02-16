<template>
  <!-- all Item -->
  <div class=" ">
    <!--  Nuvbar -->
    <div class="sticky top-0">
      <Nuvbar />
    </div>
    
    <!-- សេចក្ដីណែនាំ -->
    
    <div class="my-[200px] flex justify-around">
      <div class="textc">
        <div class="mx-[50px]">
          <p class="text-4xl font-bold">រៀនសរសេរកូដពីចំណុច​សូន្យ</p>
          <br />
          <p class="w-[90%] text-lg">
            រៀនបច្ចេកវិទ្យាថ្មីៗដូចជា កូដ និយាយជាភាសាខ្មែរ​
            និងចាប់ផ្តើមអាជីពក្នុងសម័យបច្ចេកវិទ្យា 4.0!
            ចុះឈ្មោះឥឡូវតាមតេលេក្រាម!
          </p>
        </div>
          
        <div class="py-[30px] px-40">
          <RouterLink to="">
            <button
              @click="telegram()"
              class="bg-blue-500 w-60 rounded-lg items-center p-2 text-white hover:bg-blue-400 transition-all"
            >
              ចុះឈ្មោះ
            </button>
            <div class="my-[20px] mx-[100px]">
                          <span class="loading loading-dots loading-lg"></span>

            </div>
          </RouterLink>
        </div>
      </div>

      <div class="mr-[100px] my-[-70px]">
        <img src="../pic/Untitled-1.png" alt="" />
      </div>
    </div>
    <!-- Manager -->
<div class="mger">
   <div class="bg-base-200 w-[100%] h-[360px] flex justify-between">
    <div >
        <img src="../pic/IMG_3440.JPG" class="max-w-sm rounded-lg shadow-2xl py-12" />
    </div>
    <div class=" pr-[700px] px-[30px]">
      <h1 class="  text-3xl py-[50px] font-thin ">Administrator!</h1>
      <p class="shadow-xl rounded-md p-3 font-semibold">ចូលរួមធ្វើអោយវិស័យ បច្ចេកវិទ្យានៅកម្ពុជាកាន់តែរីកចម្រើន ចូលរួមជាមួយខ្ញុំឥលូវនេះ​ ។</p>
    </div>
   </div>
</div>
  
    

    <!-- Item and box -->
    <div class="itembox">
      <div
        class="my-[80px] flex flex-wrap justify-around sm:container:gap-[30px]"
      >
       <!-- box html and css -->
        <div class="py-10">
          <div class="w-full sm:w-[350px] h-[400px] shadow-md">
            <div class="text-center">
              <img 
                 src="../pic/1.jpg" class=" w-[350px] h-[250px] "
              />
              <p>
                វគ្ក HTML and CSS : រៀនពីមូលដ្ធានគ្រឹះ​នៃភាសាកូដ HTML and CSS ។​
                ភាសានេះជាភាសាមួយសម្រាប់បង្កើត វេបសាយ។
              </p>
              <button
                class="bg-blue-500 w-30 rounded-lg items-center p-2 text-white hover:bg-blue-400 transition-all my-5"
              >
                ចាប់ផ្ដើមរៀន
              </button>
            </div>
          </div>
        </div>
        <!-- box c++ -->
        <div class="py-10">
          <div class="w-full sm:w-[350px] h-[400px] shadow-md">
            <div class="text-center">
              <img class="w-[390px] h-[250px]"
                src="../pic/reaksa.jpg" 
              />
              <p>
                វគ្ក c++ : រៀនពីមូលដ្ធានគ្រឹះ​នៃភាសាកូដ c++ ។​
                ភាសានេះជាភាសាមួយសម្រាប់អ្នករៀនកូដដំបូងគួរតែចេះ ។
              </p>
              <button
                class="bg-blue-500 w-30 rounded-lg items-center p-2 text-white hover:bg-blue-400 transition-all my-5"
              >
                ចាប់ផ្ដើមរៀន
              </button>
            </div>
          </div>
        </div>

       

        <!-- box javascript -->
        <div class="py-10">
          <div class="w-full sm:w-[350px] h-[400px] shadow-md">
            <div class="text-center">
              <img class=" w-[350px] h-[250px]"
                src="../pic/javascript.jpg"
               
              />
              <p>
                វគ្ក ​​javascript : រៀនពីមូលដ្ធានគ្រឹះ​នៃភាសាកូដ javascript ។​
                ភាសានេះជាភាសាមួយសម្រាប់បន្ថែមជាមួយភាសាកូដ HTML  and CSS ។
              </p>
              <button
                class="bg-blue-500 w-30 rounded-lg items-center p-2 text-white hover:bg-blue-400 transition-all my-5"
              >
                ចាប់ផ្ដើមរៀន
              </button>
            </div>
          </div>
        </div>

        <!-- box vue.js-->
        <div class="py-10">
          <div class="w-full sm:w-[350px] h-[400px] shadow-md">
            <div class="text-center">
              <img class="w-[350px] h-[250px]"
                src="../pic/cover_vue.png"
               
              />
              <p>
                វគ្ក Vue.js : រៀនពីមូលដ្ធានគ្រឹះ​នៃភាសាកូដ Vue.js ។​
                Vue.js ជា Framwork របស់ javascript វាកាន់តែងាយស្រួលក្នុងការបង្កើតវេបសាយជាមួយ Vue.js។
              </p>
              <button
                class="bg-blue-500 w-30 rounded-lg items-center p-2 text-white hover:bg-blue-400 transition-all my-5"
              >
                ចាប់ផ្ដើមរៀន
              </button>
            </div>
          </div>
        </div>

        
        <!-- box 3`sedr -->
      </div>
    </div>

    <!-- last -->
    <!-- This code using disey ui -->
        <div>
          <footer class="footer items-center p-4 bg-neutral text-neutral-content">
  <aside class="items-center grid-flow-col">
   <svg width="36" height="36" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd" class="fill-current"><path d="M22.672 15.226l-2.432.811.841 2.515c.33 1.019-.209 2.127-1.23 2.456-1.15.325-2.148-.321-2.463-1.226l-.84-2.518-5.013 1.677.84 2.517c.391 1.203-.434 2.542-1.831 2.542-.88 0-1.601-.564-1.86-1.314l-.842-2.516-2.431.809c-1.135.328-2.145-.317-2.463-1.229-.329-1.018.211-2.127 1.231-2.456l2.432-.809-1.621-4.823-2.432.808c-1.355.384-2.558-.59-2.558-1.839 0-.817.509-1.582 1.327-1.846l2.433-.809-.842-2.515c-.33-1.02.211-2.129 1.232-2.458 1.02-.329 2.13.209 2.461 1.229l.842 2.515 5.011-1.677-.839-2.517c-.403-1.238.484-2.553 1.843-2.553.819 0 1.585.509 1.85 1.326l.841 2.517 2.431-.81c1.02-.33 2.131.211 2.461 1.229.332 1.018-.21 2.126-1.23 2.456l-2.433.809 1.622 4.823 2.433-.809c1.242-.401 2.557.484 2.557 1.838 0 .819-.51 1.583-1.328 1.847m-8.992-6.428l-5.01 1.675 1.619 4.828 5.011-1.674-1.62-4.829z"></path></svg> 
    <p>Copyright © 2024 - reaksa - v-code</p>
  </aside> 
  <nav class="grid-flow-col gap-4 md:place-self-center md:justify-self-end">
    <a><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" class="fill-current"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"></path></svg>
    </a>
    <a><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" class="fill-current"><path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"></path></svg></a>
    <a><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" class="fill-current"><path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"></path></svg></a>
  </nav>
</footer>

        </div>
  </div>
</template>

<script>
import Nuvbar from "./Nuvbar.vue";
import Boxitem from "./Boxitem.vue";
export default {
  setup() {
    return {};
  },
  components: {
    Nuvbar,
    Boxitem,
  },
  methods: {
    telegram() {
      const telegramURL = "https://t.me/+5ucgCPwyA31kYjNl";
      // Redirect the user to the Telegram link
      window.location.href = telegramURL;
    },
  },
};
</script>

<style scoped>
@media screen and (max-width: 778px) {
  .itembox img {
    
    margin-left: 50px;
  }
  .textc{
     margin-left: 130px;
  }
  .mger img{
   margin-left: 25px;
  }
  .mger p{
    margin-top: 250px;
    margin-left: -400px;
    margin-right: 200px;
  }
  .mger h1{
    opacity: 0;
  }
  .mger{
    margin-top: -100px;
  }
}
</style>
