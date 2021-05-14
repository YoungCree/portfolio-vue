<template>
  <div class="home">
    <img src="@/assets/images/home-img.jpg" class="home-img">
  </div>
</template>

<script>
// @ is an alias to /src

export default {

}
</script>

<style media="screen">
.home-img {
  width: 100%;
  -webkit-clip-path: polygon(0 0, 0 100%, 100% 20%, 100% 0) !important;
  clip-path: polygon(0 0, 0 80%, 100% 65%, 100% 0) !important;
  margin-top: -80px;
}

.md-transparent {
  box-shadow: black 0px 30px 50px -1em inset !important;
  color: white !important;
}

.nav-btn, .md-title {
  color: white !important;
}
</style>
