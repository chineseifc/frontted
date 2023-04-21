<script setup>
import Ido from './components/Ido.vue'
import ConnectWallet from './components/ConnectWallet.vue'
</script>

<template>
  <div class= "header">
  <ConnectWallet />
  </div>
  <div>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/cxelogo.svg" class="logo vue" alt="CXE" />
    </a>
  </div>
  <Ido msg="Develop EOS-EVM" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.header{
  top:10px;
  position:absolute;
  right:20px;
}
</style>
