<template>
  <div class="serv">
    <h3>services</h3>
    <div class="serv__list"></div>
  </div>
</template>

<script>
export default {
  name: "HomeServices",
};
</script>

<style lang="scss" scoped>
.serv {
  background: rgb(135, 133, 133);
  width: 49%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 400px;
  border-radius: 10px;
  &__list {
    border: solid 1px #fff;
  }
}
</style>
