<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="wrapper">
      <div>
      </div>
      <div class="nav-links">
          <RouterLink to="/" class="router">Home</RouterLink>
          <RouterLink to="/about" class="router">About</RouterLink>
      </div>
    </div>
  <RouterView />
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;700&family=Rubik:wght@300;400;500;700&display=swap');
*{
  font-family: 'Roboto', sans-serif;
  color: white;
}
.wrapper{
  width: 100%;
  display: grid;
  grid-template-columns: 88% 12%;
  padding: 20px 10px;
}
.router {
  font-family: 'Roboto', sans-serif;
  text-decoration: none;
  color: inherit;
}
.nav-links {
  display: flex;
  justify-content:space-around;
}

</style>
