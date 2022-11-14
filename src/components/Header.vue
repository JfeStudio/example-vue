<script setup>
defineProps({
  name: String,
  role: String,
});
</script>

<template>
  <div class="navbar">
    <div class="col-header">
      <img class="images-hero" src="../assets/images/hero.jfif" alt="hero" />
    </div>
    <div class="col-header">
      <h1 class="title">{{ name }}</h1>
      <p class="role">{{ role }}</p>
      <div class="btn-header">
        <button type="submit">Download CV</button>
        <button type="submit">Readme</button>
      </div>
    </div>
  </div>
</template>
