<template>
  <div class="home">
    <div class="limiter">
      <div class="container-login100">
        <div class="wrap-login100">

          <form class="login100-form validate-form">
            <span class="login100-form-title">
              Login
            </span>

            <div class="wrap-input100 validate-input" data-validate = "Valid email is required: ex@abc.xyz">
              <input class="input100" type="text" name="email" placeholder="Email">
              <span class="focus-input100"></span>
              <span class="symbol-input100">
                <i class="fa fa-envelope" aria-hidden="true"></i>
              </span>
            </div>

            <div class="wrap-input100 validate-input" data-validate = "Password is required">
              <input class="input100" type="password" name="pass" placeholder="Password">
              <span class="focus-input100"></span>
              <span class="symbol-input100">
                <i class="fa fa-lock" aria-hidden="true"></i>
              </span>
            </div>

            <div class="container-login100-form-btn">
              <button class="login100-form-btn">
                Login
              </button>
            </div>

            <div class="text-center p-t-12">
              <span class="txt1">
                Belum punya akun?
              </span>
              <a class="txt2" href="#">
                <router-link to="/about">Register?</router-link>
              </a>
            </div>
          </form>

          <div class="login100-pic js-tilt" data-tilt>
            <img src="../assets/images/img-02.png">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
