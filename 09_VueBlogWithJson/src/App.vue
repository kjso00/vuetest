<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/post">Post</RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
</template>

<style scoped>
header {
  background-color: #f8f9fa;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  padding: 20px;
  width: 100%;
}

nav {
  display: flex;
  justify-content: center;
  align-items: center;
}

a {
  margin: 0 15px;
  font-size: 18px;
  color: #007bff;
  text-decoration: none;
  transition: color 0.3s ease-in-out;
}

a:hover {
  color: #0056b3;
}

a.active {
  font-weight: bold;
  border-bottom: 2px solid #0056b3;
}

.RouterLink {
  margin-left: 10px;
  font-size: 20px;
}

</style>
