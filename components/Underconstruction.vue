<template>
  <div>
    <div class="bg-image"></div>
    <div class="bg-text">
      <h1 class="title">Under construction</h1>
      <p class="sub-title">I will be back soon!</p>
    </div>
  </div>
</template>

<script lang="ts">
export default {}
</script>

<style>
.title {
  @apply text-4xl;
  @apply font-sans;
}
.sub-title {
  margin-top: 12px;
  @apply text-2xl;
  @apply font-sans;
}
.bg-text {
  background-color: rgb(0, 0, 0); /* Fallback color */
  background-color: rgba(0, 0, 0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 60%;
  height: auto;
  padding: 20px;
  text-align: center;
}
.bg-image {
  display: flex;
  background-image: url('../assets/bg-ijen.jpg');
  filter: blur(16px);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
}
</style>
