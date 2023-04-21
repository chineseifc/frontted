<script setup>

defineProps({
  msg: String,
})

</script>

<template>
  <h2>{{ msg }}</h2>

  <div class="card">
    <button type="button" @click="">参与预售</button>
  </div>

  <p>
    <a href="https://github.com/chineseifc/Promote-the-development-of-EOS-EVM-token" target="_blank">
      <img src="../assets/github.svg" class="logo vue" alt="github" />
    </a>
    <a href="https://t.me/cxeos" target="_blank">
      <img src="../assets/telegram.svg" class="logo vue" alt="telegram" />
    </a>
  </p>
  
  <p class="read-the-docs">助力EOS-EVM发展</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
