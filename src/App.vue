<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div id="layout">
    <header>
      <div class="wrapper">
        <nav>
          <RouterLink to="/">Home</RouterLink>
          | <RouterLink to="/about">About</RouterLink>
        </nav>
      </div>
    </header>

    <RouterView />
  </div>
</template>

<style scoped>
#layout{
  text-align: center;
}
nav{
  padding: 30px;
}
nav a{
  font-weight: bold;
}
nav a.router-link-exact-active{
  color: red;
}

</style>
