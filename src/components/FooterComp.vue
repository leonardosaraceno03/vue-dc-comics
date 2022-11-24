<template>
  <footer>
    <div class="container">
      <div>
        <ul>
          <li><a href="">Link</a></li>
          <li><a href="">Link</a></li>
          <li><a href="">Link</a></li>
          <li><a href="">Link</a></li>
          <li><a href="">Link</a></li>
        </ul>
      </div>
      <div>
            <div class="div-logo-bg">
                <img class="dc-logo-bg" src="../assets/img/dc-logo-bg.png" alt="" />
            </div>
            
      </div>
    </div>
  </footer>
</template>


<script>
export default {
  name: "FooterComp",
  props: {
    msg: String,
  },
};
</script>
<style lang="scss" scoped>
footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover; 
  z-index: 0;
}
a {
  color: white;
}
.container {
  margin: 0 auto;
  width: 80%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 300px; 
}
.dc-logo-bg{
  
}

</style>
