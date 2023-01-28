<template>
  <nav>
    <ul>
      <li>
        <router-link to="/about">About</router-link>
      </li>
      <li>
        <router-link to="/">Home</router-link>
      </li>
    </ul>
  </nav>
</template>

<script setup>
</script>

<style>
nav {
  background-color: #333;
  color: #fff;
  padding: 1rem;
}

ul {
  list-style: none;
  display: flex;
  flex-direction: row-reverse;
}

li {
  margin: 0 1rem;
}

a {
  color: #fff;
  text-decoration: none;
}
</style>