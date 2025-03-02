<script setup>
import './assets/css/main.css';
</script>

<template>
  <div id="bar">
    <div>
      <span id="title1">LUKE</span><span id="title2">WALTER</span>
      <span class="link"><NuxtLink to="/">About Me</NuxtLink></span>
      <span class="link"><NuxtLink to="/portfolio">Portfolio</NuxtLink></span>
      <span class="link"><NuxtLink to="/tutoring">Tutoring</NuxtLink></span>
      <span class="link"><NuxtLink to="/freelance">Freelance</NuxtLink></span>
      <span class="link"><button>Contact</button></span>
    </div>
    <div>
      <span class="icon"><a href="https://www.linkedin.com/in/luke-walter-841a23167/" target=”_blank”><Icon name="uil:linkedin" style="color: white" /></a></span>
      <span class="icon"><a href="https://github.com/LukeWalter" target=”_blank”><Icon name="uil:github" style="color: white" /></a></span>
      <span class="icon"><a href="https://discord.com/users/317812947143622658"><Icon name="uil:discord" style="color: white" /></a></span>
    </div>
  </div>
  <div style="height: 70px;" />
</template>

<style>
#bar {
    padding: 20px;
    position: fixed;
    display: flex;
    width: 100%;
    height: 70px;
    color: white;
    background-color: black;
    box-sizing:border-box;
    align-items: center;
    justify-content: space-between;
}
#title1 {
    user-select: none;
    font-weight: bold;
    font-style: normal;
    font-size: 36px;
}
#title2 {
    user-select: none;
    font-style: normal;
    font-size: 36px;
    color: #C9C9C9;
    padding-right: 20px;
}
.link + .link {
    padding-left: 20px;
}
a {
    user-select: none;
    color: #C9C9C9;
    height: 100%;
    text-decoration: none;
}
a:hover {
    user-select: none;
    color: white;
    height: 100%;
    background-image: linear-gradient(black, white);
}
</style>