<template>
  <div>
    <button class="g-button">hi</button>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style lang="scss"  scoped>
  .g-button{
    font-size: var(--font-size);
    height: var(--button-height);
    padding: 0 1em;
    border-radius: var(--border-radius);
    border:1px solid var(--border-color);
    background-color: var(--button-bg);
    &:hover{
    border-color: var(--border-color-hover);
    }
    &:active{
      background-color: var(--border-active-bg);
    }
    &:focus{
      outline: none;
    }
  }
</style>