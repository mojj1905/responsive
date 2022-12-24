<template>
  <div class="container-fluid">
    <div>
      <div class="about_">
        <div class="row">
          <div class="col-6" id="about_1">
            <div class="about-title">
              <h1>About <span>Us.</span></h1>
              <p>
                UI transformed music listening forever when it launched in 2008.
                Discover,manage and share over 80 million tracks,including 4.7
                million podcasts,for free, or upgrade to UI Premium to access
                exclusive features for music including improved sound quality
                and an on-demand, offline,and ad-free music listening
                experience.<br>Our missionis to unlock the potential of human
                creativity—by giving a million creative artists the opportunity
                to live off their art and billions of fans the opportunity to
                enjoy and be inspired by it.
              </p>
            </div>
            <div class="about_ul">
              <div class="about_div d-flex">
                <ul type="square">
                  <li><a href="#">Lorem ipsum dolor.</a></li>
                  <li><a href="#">Lorem ipsum dolor.</a></li>
                </ul>
                <ul type="square" class="offset-3">
                  <li><a href="#">Lorem ipsum dolor.</a></li>
                  <li><a href="#">Lorem ipsum dolor.</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-6"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {},
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Krub:ital,wght@0,200;0,300;1,200&display=swap");

.about-title h1 {
  font-size: 61px;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
}
.about-title span {
  font-size: 61px;
  letter-spacing: 6px;
  color: #aa84f9;
  font-weight: 400;
  font-family: "Krub";
}
.about-title p {
  width: auto;
  font-size: 14px;
  color: #ffffff;
  font-weight: 600;
  font-family: "Krub";
  margin-top: 45px;
}
.about_ul li {
  font-size: 12px;
  line-height: 22px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  font-family: "Krub";
  margin-top: 50px;
  /* margin-bottom: 100px; */
}
.about_div ul li {
  color: #aa84f9 !important;
}
.about_div a {
  color: #ffffff;
  text-decoration: none;
}
#about_1 {
  margin-top: 200px;
  margin-left: 30px;
}

.about_ {
  background-image: url("../assets/img/aboutbg.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-bottom: 100px;
}
.container-fluid {
  background-color: #181818;
}
</style>