<script setup>
import './assets/css/main.css';
</script>

<template>
  <div style="height: 70px;" />
  <div id="center">
    <div id="temp-popup">
      <p>Still working on the site. Feel free to check out my socials in the meantime!</p>
      <a href="https://www.linkedin.com/in/luke-walter-841a23167/" target=”_blank”><Icon name="uil:linkedin" style="color: black; width: 70px; height: 70px;" /></a>
      <a href="https://github.com/LukeWalter" target=”_blank”><Icon name="uil:github" style="color: black; width: 70px; height: 70px;" /></a>
      <a href="https://discord.com/users/317812947143622658"><Icon name="uil:discord" style="color: black; width: 70px; height: 70px;" /></a>
    </div>
  </div>
</template>

<style>
#center {
  display: flex;
  align-items: center;
  justify-content: center;
}

#temp-popup {
  background-color: white;
  color: black;
  width: 50%;
  padding: 20px;
  text-align: center;
  border-radius: 5px;
}
</style>