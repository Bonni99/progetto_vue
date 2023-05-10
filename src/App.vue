<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Gallery from './components/Gallery.vue'

</script>

<template>
  <header>
    
    <div class="wrapper">
      
        
      
    </div>
  </header>

  <main>
    <div class="gallery">
    <Gallery msg="Streetwear" />
      <Gallery msg="Music" />
        <Gallery msg="Festival" />
  </div>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

.gallery{
  display:flex;
  align-items: flex-start;
  
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
