<template>
  <header class="main">
    <nav>
      <a href="/" class="logo">
        <img src="/logo.png" alt="logo" />
      </a>

      <ul>
        <li><a href="/about">Hi</a></li>
        <li><a class="btn" @click="write">Write</a></li>
      </ul>
    </nav>
  </header>
</template>

<script setup lang="ts">
const write = () => {
  alert("Hello");
};
</script>