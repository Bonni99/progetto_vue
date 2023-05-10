
<script setup>
defineProps({
  title: {
    type: String,
    imageUrl: String,  }
})
</script>




<template>

<article class="article">
  <img src="src/image/vale-rjVM5h_e5yA-unsplash.jpg" width="200" alt="">
  <h2>Gallery 
     <p>Questo è un paragrafo per questo articolo</p>
  </h2>
</article>
</template>

<style scoped>




img{
  position: absolute;
  display: block;
  z-index: -10

  
}

p{
margin-right: 15px;
}

h2{
  margin: 15px;
  padding: 9px;
  display:block;
  width: 30%;
  display: block;
  
  font-weight: 700;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: medium;


  color: #fff;

}

.article :hover{
  color: linear-gradient(0deg, blue, white);

}


h1{
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  font-weight: 800;
  }



</style>

