<template>
  <div class="top-content" style="position: relative; z-index: 0; background: none;">
    <div class="container">

      <div class="row">
        <div class="col-sm-8 col-sm-offset-2 text">
          <h1 class="wow fadeInLeftBig animated" style="visibility: visible; animation-name: fadeInLeftBig;">Register Page</h1>
          <div class="description wow fadeInLeftBig animated" style="visibility: visible; animation-name: fadeInLeftBig;">
            <p>
              Hello u can register to watch paid movies and series in the site.
            </p>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-6 col-sm-offset-3 r-form-1-box wow fadeInUp animated" style="visibility: visible; animation-name: fadeInUp;">
          <div class="r-form-1-top">
            <div class="r-form-1-top-left">
              <h3>Sign up now</h3>
              <p>Fill in the form below to get instant access:</p>
            </div>
            <div class="r-form-1-top-right">
              <i class="fa fa-pencil"></i>
            </div>
          </div>
          <div class="r-form-1-bottom">
            <form role="form" action="" method="post">
              <div class="form-group">
                <label class="sr-only" for="r-form-1-name">name</label>
                <input type="text" name="r-form-1-name" placeholder="name..." class="r-form-1-name form-control" id="r-form-1-name">
              </div>
              <div class="form-group">
                <label class="sr-only" for="r-form-1-email">Email</label>
                <input type="email" name="r-form-1-email" placeholder="Email..." class="r-form-1-email form-control" id="r-form-1-email">
              </div>
              <div class="form-group">
                <label class="sr-only" for="r-form-1-username">Username</label>
                <input type="text" name="r-form-1-username" placeholder="Username..." class="r-form-1-username form-control" id="r-form-1-username">
              </div>
              <div class="form-group">
                <label class="sr-only" for="r-form-1-password">Password</label>
                <input type="password" name="r-form-1-password" placeholder="Password..." class="r-form-1-password form-control" id="r-form-1-password">
              </div>
              <div class="form-group">
                <label class="sr-only" for="r-form-1-about-yourself">About yourself</label>
                <textarea name="r-form-1-about-yourself" placeholder="About yourself..." class="r-form-1-about-yourself form-control" id="r-form-1-about-yourself"></textarea>
              </div>
              <button type="submit" class="btn">Sign me up!</button>
            </form>
          </div>
        </div>
      </div>

    </div>
    <div class="backstretch">
      <div class="image"></div>
    </div></div>
</template>

<script>
    export default {

    }
</script>

<style>

</style>
