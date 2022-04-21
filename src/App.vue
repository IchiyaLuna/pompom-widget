<template>
  <img class="tachie" src="./assets/pompomrice.png" />
</template>

<script setup></script>

<style>
  html,
  body {
    width: min-content;
    margin: 0;
  }
  #app {
    text-align: center;
  }

  .tachie {
    max-height: 400px;
    -webkit-app-region: drag;
    animation: motion 0.8s linear 0s infinite alternate;
  }

  @keyframes motion {
    0% {
      margin-top: 0px;
    }
    100% {
      margin-top: 10px;
    }
  }
</style>
