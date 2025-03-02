<template>
  <Navbar />
  <div id="content">
    <slot />
  </div>
</template>

<style>
body {
    margin: 0;
    
}
#content {
    background-image: linear-gradient(#2D2847, #6E61AD);
    width: 100%;
    min-height: 100vh;
}
</style>