<script setup>
</script>

<template>
  <main>
    <h1 class="heading">Hello User!</h1>
    <p class="heading-sub">A website made by Dan</p>
    <br>
    <br>
    <div class="games">
      <RouterLink to="/TodoList" class="router">
      <div class="game-container game1"></div>
      </RouterLink>
      <div class="game-container">
  
      </div>
      <div class="game-container">
  
      </div>
      <div class="game-container">
  
      </div>
      <div class="game-container">
  
      </div>
      <div class="game-container">
  
      </div>
    </div>
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kalam:wght@300;400;700&family=Roboto:wght@100;300;400;700&family=Rubik:wght@300;400;500;700&display=swap');
.heading{
  text-align: center;
  font-family: 'Kalam', cursive;
  font-size: 70px;
}
.heading-sub{
  margin-top: -4%;
  text-align: center;
  font-size: 15px;
}
.games{
  padding: 0 50px ;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
}
.game-container{
  position: relative;
  height: 250px;
  background-color: white;
  border: 4px solid black;
  border-radius: 15px;
}

.game-container:hover {
  transform: scale(1.02); /* Increase size by 2% on hover */
}
.game1{
  background: url('../assets/todo.jpg') center/contain no-repeat;
  background-color: white;
}
</style>
