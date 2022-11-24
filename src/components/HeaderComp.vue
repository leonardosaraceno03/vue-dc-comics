<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="logo">
    <nav>
      <ul>
        <li><a href="#">
CHARACTERS   
          </a></li>
        <li class="active"><a href="#">
COMICS         
          </a></li>
        <li><a href="#">
MOVIES         
          </a></li>
        <li><a href="#">
TV          
          </a></li>
        <li><a href="#">
GAMES          
          </a></li>
        <li><a href="#">
VIDEOS          
          </a></li>
        <li><a href="#">
NEWS          
          </a></li>
        <li><a href="#">
COLLECTIBLES          
          </a></li>
        <li><a href="#">
LINK          
          </a></li>
        <li><a href="#">
          
LINK          </a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
 
}
</script>


<style scoped lang="scss">
header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  width: 80%;
  margin: 0 auto;
  
}
ul{
  display: flex;
  gap: 10px;
}
.active{
  border-bottom: 2px solid #0282f9;
}

</style>
