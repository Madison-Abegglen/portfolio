<template>
  <div class="row bar">
    <div class="col-12 items">
      <h1>Madison Abegglen</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbar"
};
</script>

<style scoped>
.bar {
  height: 10vh;
  background-color: rgb(196, 196, 196);
}
.items {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
</style>
