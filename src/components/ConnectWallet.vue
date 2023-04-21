<script setup>

</script>

<template>
  
  <button class= "but0" scale= "sm" type="button" @click="get">
    <div class= "but1" display= "none,,,block">连接钱包</div>
    <div class= "but2" display= "block,,,none">连接</div>
  </button>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.but0{
  position: relative;
    -webkit-box-align: center;
    align-items: center;
    border: 0px;
    border-radius: 16px;
    box-shadow: rgba(14, 14, 44, 0.4) 0px -1px 0px 0px inset;
    cursor: pointer;
    display: block;
    font-family: inherit;
    font-size: 16px;
    font-weight: 600;
    -webkit-box-pack: center;
    justify-content: center;
    letter-spacing: 0.03em;
    line-height: 1;
    opacity: 1;
    outline: 0px;
    transition: background-color 0.2s ease 0s, opacity 0.2s ease 0s;
    height: 32px;
    padding: 0px 16px;
    background-color: var(--colors-primary);
    color: var(--colors-invertedContrast);
}
.but1{
  display: none;
}
.bu2{
  display: block;
}
</style>
