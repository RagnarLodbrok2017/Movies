<template>
  <div class="limiter">
    <div class="container-login100">
      <div class="head col-xs-12 wow fadeInLeftBig animated">
        Galaxy Movies
      </div>
      <div class="wrap-login100 p-t-190 p-b-30 wow fadeInUp animated">
        <form class="login100-form validate-form">
          <div class="login100-form-avatar">
          </div>

          <div class="wrap-input100 validate-input m-b-10" data-validate = "Username is required">
            <input class="input100" type="text" name="username" placeholder="Username" v-model="username">
            <span class="focus-input100"></span>
            <span class="symbol-input100">
              <i class="fa fa-user"></i>
            </span>
          </div>

          <div class="wrap-input100 validate-input m-b-10" data-validate = "Password is required">
            <input class="input100" type="password" name="pass" placeholder="Password">
            <span class="focus-input100"></span>
            <span class="symbol-input100">
              <i class="fa fa-lock"></i>
            </span>
          </div>

          <div @click='test' class="container-login100-form-btn p-t-10">
            <button class="login100-form-btn">
              Login
            </button>
          </div>

          <div class="text-center w-full p-t-25 p-b-230">
            <a href="#" class="txt1">
              Forgot Username / Password?
            </a>
          </div>

          <div class="text-center w-full">
            <a class="txt1" href="#">
              Create new account
              <i class="fa fa-long-arrow-right"></i>            
            </a>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
      data(){
        return{
          username:"",
        }
      },
      methods:{
        test(){
          this.$http.get('http://localhost:8000/api/test').then(
            function(response){
              console.log(response);
            }
            );
        }
      },
    }
</script>
