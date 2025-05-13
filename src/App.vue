<script setup>
import HomePage from './home/HomePage.vue'
import RobotBuilder from './build/RobotBuilder.vue'
</script>

<template>

  <header>
    <nav>
      <ul>
        <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png" alt="">
        </li>
      </ul>
    </nav>
  </header>
  <main>
    <!-- <HomePage/> -->
    <RobotBuilder/>
  </main>

</template>

<style scoped>
body{
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}
#app{
  font-family: Arial, Helvetica, sans-serif;
}
main{
  margin: 0 auto;
  padding: 30px;
  background-color: #999;
  width: 1024px;
  min-width: 300px;
  margin-top: 50px;
}
header{
  background-color: #999;
  width: 1024px;
  margin: 0 auto;
  position: absolute;
}
ul{
  padding: 3px;
  display: flex;
}
.nav-item{
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo{
  vertical-align: middle;
  height: 30px;
}
</style>
