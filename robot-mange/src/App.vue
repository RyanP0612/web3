<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <main id="card-app">

  
  <div id="content-app">
    
  </div>
  <header>
    

    <div class="wrapper">
      <HelloWorld msg="vinicius jr e paqueta" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <h1></h1>
        <RouterLink to="/cart">Cart</RouterLink>
        <h1></h1>

        <RouterLink to="/build">Build</RouterLink>

      </nav>
    </div>
  </header>

  <RouterView />
  </main>
</template>

<style scoped>

</style>
