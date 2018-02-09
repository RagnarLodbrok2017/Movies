<template>
  <nav class="navbar navbar-inverse col-lg-12">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#"><span>Galaxy</span></a>
      </div>
      <!-- Collect the nav links, forms, and other content for toggling -->
      <div class="collapse navbar-collapse">
        <ul class="nav navbar-nav navbar-right">
          <li><a class="scroll-link" href="#">Features</a></li>
          <li><a class="scroll-link" href="#">How it works</a></li>
          <li><a class="scroll-link" href="#">Testimonials</a></li>
          <li><a class="scroll-link" href="#">FAQ</a></li>
          <li class="dropdown">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Signin/Signup<span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="/login"><span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>Signin</a></li>
              <li role="separator" class="divider"></li>
              <li><a href="#"><span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>SignUp</a></li>
            </ul>
          </li>
        </ul>
      </div>
  </nav>
</template>

<script>
    export default {

    }
</script>

<style scoped>

</style>
