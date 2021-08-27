<template>
  <div class="home">
    <div class="title-div">
      <img src="@/assets/images/home-img.jpg" class="home-img">
      <div class="big-name">
        <div class="first-name">Corey</div>
        <div class="last-name">Devenport</div>
      </div>
    </div>
    <div class="work-exp-div">
      <md-card md-with-hover>
        <md-ripple>
          <md-card-header>
            <div class="md-title">Card with hover effect</div>
            <div class="md-subhead">It also have a ripple</div>
          </md-card-header>

          <md-card-content>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
          </md-card-content>

          <md-card-actions>
            <md-button>Action</md-button>
            <md-button>Action</md-button>
          </md-card-actions>
        </md-ripple>
      </md-card>
      <div>Bose Corp</div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {

}
</script>

<style media="screen">
.title-div {
  position: relative;
}

.home-img {
  width: 100%;
  -webkit-clip-path: polygon(0 0, 0 100%, 100% 20%, 100% 0) !important;
  clip-path: polygon(0 0, 0 80%, 100% 65%, 100% 0) !important;
  margin-top: -80px;
}

.big-name {
  position: absolute;
  top: 70px;
  left: 50px;
}

.first-name {
  font-size: 100px;
  color: white;
  height: 100px;
  width: 270px;
  background-color: rgb(255, 86, 80);
  padding-top: 50px;
}

.last-name {
  font-size: 120px;
  color: white;
  background-color: rgb(255, 86, 80);
  height: 120px;
  padding-top: 40px;
}

.md-transparent {
  box-shadow: black 0px 30px 50px -1em inset !important;
  color: white !important;
}

.nav-btn, .md-title {
  color: white !important;
}
</style>
