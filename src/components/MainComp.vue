<template>
    <main>
        <section id="products">
            <h2>Il contenuto andrà qui</h2>
        </section>
        <section>
            <div id="dc-images">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>text</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>text</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>text</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>text</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>text</span>
            </div>
            </div>
           
        </section>
    </main>
</template>
<script>
export default {
  name: 'MainComp',
  props: {
    msg: String
  }
}
</script>
<style scoped lang="scss">

#dc-images{
    background-color: #0282f9;
    display: flex;
    align-content: center;
    justify-content: space-around;
    padding: 30px 0px;
}
div{
    display: flex;
    gap: 10px;
    align-content: center;
    color: white;
    font-weight: bold;
}
img{
    height: 50px;
}
span{
    display: flex;
    align-items: center;
}
main{
    z-index: 1;
}
</style>