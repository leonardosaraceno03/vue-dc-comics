<template>
  <div class="Utilities">
    <div class="linkspace">
      <div>
        <div>
          <ul>
            <li><h2>DC COMICS</h2></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul>
            <li><h2>SHOPE</h2></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div>
          <ul>
            <li><h2>DC</h2></li>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscription</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratinggs</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div>
          <ul>
            <li><h2>SITES</h2></li>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <!--immagine logo -->
      <div class="cutimage">
      </div>
    </div>
    <div class="singUp dflex vcenterItems">
      <div class="correction">
        <div class="vcenterSelf">
          <button href="#" class="buttonSingUp">SING UP NOW!</button>
        </div>
        <div class="dflex vcenterItems">
          <h2 class="followUs">FOLLOW US</h2>
          <div class="imgSettings">
            <img src="../assets/img/footer-facebook.png" alt="facebook" />
            <img src="../assets/img/footer-twitter.png" alt="twitter" />
            <img src="../assets/img/footer-youtube.png" alt="youtube" />
            <img src="../assets/img/footer-pinterest.png" alt="pinterest" />
            <img src="../assets/img/footer-periscope.png" alt="periscope" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.Utilities {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

ul {
  list-style-type: none;
}
li {
  color: white;
}
a {
  color: rgb(179, 176, 176);
  text-decoration: none;
}

.linkspace {
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
}
.linkspace > div {
  display: flex;
  padding: 20px;
}
.cutimage {
  background-image: url('../assets/img/dc-logo-bg.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 50%;
}

.singUp {
  width: 100vw;
  z-index: 0;
  background-color: #333333;
  
}
.correction {
  width: 80%;
  margin: auto;
  display: flex;
  justify-content: space-between;
}
.buttonSingUp {
  color: white;
  background-color: #333333;
  border: 2px solid #007cf2;
  padding: 10px;
  font-size: 1rem;
}
.followUs {
  color: #007cf2;
}
.dflex{
  display: flex;
}
.vcenterItems{
  align-items: center;
}
.vcenterSelf{
  align-self: center;
}
.imgSettings img{
  margin: auto 10px;
}
</style>