<template>
  <header>
    <nav>
      <div><img src="../assets/img/dc-logo.png" alt="logo" /></div>
      <div class="list">
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </div>
    </nav>
    <div class="content">
      <div class="jumbotron">
        <button>CURRENT SERIES</button>
      </div>
      <div class="cards">

      </div>
    </div>
  </header>
</template>
  


<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss" >
 header{
  background-color: white;
}
nav{
  display: flex;
  justify-content: space-between;
  width: 80%;
  margin: auto;
}
/*****************************
               LISTA
*******************************/
.lista{
  align-self: center;
}
ul {
  list-style-type: none;
  display: flex;
}
li {
  margin: auto 10px;
}
a {
  color: black;
  text-decoration: none;
  font-weight: bold;
}
a:hover {
  color: rgb(64, 174, 211);
  border-bottom: 5px solid rgb(64, 174, 211);
  padding-bottom: 25px;
}
/********************
       CONTENT
*********************/
.content {
  background-color: #1f1f1f;
}

/********************
      JUMBOTRON
*********************/
.jumbotron{
  background-image: url('../assets/img/jumbotron.jpg');
  height: 400px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top;
  position: relative;
}
.jumbotron > button{
  color: white;
  font-weight: bold;
  border: 2px solid #007cf2;
  background-color: #007cf2;
  padding: 10px 40px;
  position: absolute;
  left: 15%;
  bottom: -5%;
}
</style>