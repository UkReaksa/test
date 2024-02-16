<template>
       <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
        
    <!-- logo -->
<div class=" sticky top-0 bg-slate-50 w-[100%]">
    <nuvbar/>


     <div class="bgg">
        <!-- login using code disey ui -->
    <div class="hero min-h-screen bg-base-100">
  <div class="hero-content flex-col lg:flex-row-reverse">
    <div class="text-center lg:text-left">
      <h1 class="text-5xl font-bold">Login now!</h1>
      <p class="py-6">សូមបំពេញ អ៊ីម៉ែលនឹងលេខកូដអោយបានត្រឹមត្រូវ</p>
    </div>
    <div class="card shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
      <form class="card-body">
        <div class="form-control">
          <label class="label">
            <span class="label-text">Email</span>
          </label>
          <input type="email" placeholder="email" class="input input-bordered" required />
        </div>
        <div class="form-control">
          <label class="label">
            <span class="label-text">Password</span>
          </label>
          <input type="password" placeholder="password" class="input input-bordered" required />
          <label class="label">
            <a href="#" class="label-text-alt link link-hover">Forgot password?</a>
          </label>
        </div>
        <div class="form-control mt-6">
          <button class="btn btn-primary">Login</button>
        </div>
      </form>
    </div>
  </div>
    </div>
   
    </div>

</div>
  



</template>

<script>
import Nuvbar from './Nuvbar.vue';

export default {
    setup() {
        return {};
    },
    components: { Nuvbar }
}
</script>

<style scoped>

@media screen and (max-width: 778px) {
.bgg{
    margin-top: 100px;
    margin-left: 0px;
    background-color: rgba(237, 237, 237, 0.55);
    height: 130vh;
}
/* body{
    background-color: rgb(98, 92, 92);
} */

}
   


</style>