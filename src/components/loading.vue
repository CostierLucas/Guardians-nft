<template>
  <div :class="{ loader: true, fadeout: !isLoading }">
      <img width="300" src="../assets/guardians.gif" alt="">
      Loading ...</div>
</template>

<script>
export default {
  name: "LoadingScreen",
  props: ["isLoading"],
};
</script>


<style scoped>
.loader {
  height: 100%;
  background-color: #000;
  color: white;
  text-align: center;
  font-family: Orbitron;
  font-size: 32px;
  position: absolute;
  margin: auto;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  flex-direction: column;
}

.fadeout {
  animation: fadeout 2s forwards;
}

@keyframes fadeout {
  to {
    opacity: 0;
    visibility: hidden;
  }
}
</style>