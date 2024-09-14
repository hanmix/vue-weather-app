<template>
  <nav class="navbar">
    <button @click="$store.commit('toggleButton')" class="toggle">
      <font-awesome-icon class="icon" :icon="['fas', 'bars-staggered']" style="color: #000;"/>
    </button>
    
  </nav>
</template>

<script setup>

</script>

<style lang="scss">
  .navbar {
    background: #fff;
    width: 100%;
    padding: 20px;
    display: flex;
    justify-content: end;
  }

  button {
    border: none;
    background: transparent;
    cursor: pointer;
  }

  .icon {
    color: #333;
    font-size: 24px;
  }
</style>