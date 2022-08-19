<template>
  <div class="main-div">
    <div class="pt-10 px-10 text-center w-full">
      <p class="desktop:text-5xl lg:text-6xl md:text-5xl sm:text-4xl pt-3 px-1 mt-1 text-white">Heroes of Olympus</p>
    </div>

    <div class="p-10 desktop:mt-10">
      <router-view />
    </div>
  </div>
</template>

<script>
</script>

<style>

p, span {
  color: white;
}

.main-div-color {
  background-color: red;
}
.main-div {
  position: relative;
  display: flex;
  flex-direction: column;
}

.main-bg-color {
  background-color: rgb(15, 16, 38);
}

.container {
  border: 2px solid white;
  padding: 20px;
}

.prim-button {
  background-color: rgb(34, 211, 238);
}

.prim-button:hover {
  background-color: rgb(8, 145, 178);
  color: white;
}

@font-face {
  font-family: 'Main';
  src: url(./assets/Dalek.ttf);
}

body {
  background-color: rgb(15, 16, 38);
  margin: 0;
  padding: 0;
}

* {
  font-family: 'Main';
}
input[type='radio']:checked + span {
  @apply text-black;
}
</style>
