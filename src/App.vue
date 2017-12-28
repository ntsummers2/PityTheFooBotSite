<template>
  <video autoplay loop id='pityDaFooVideo'>
    <source src='static/shutupfoo.mp4' type='video/mp4'>
  </video>
</template>

<script src='https://www.gstatic.com/firebasejs/4.8.1/firebase.js'></script>

<script>

export default {
  name: 'app',
  components: {
  }
}
</script>

<style>
html, body {
  margin:0; padding: 0;
  height: 100%; width: 100%;
  background: #000;
}

#pityDaFooVideo {
    position: fixed;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
}
</style>
