<template>
  <div class="serv">
    <ul class="serv__list">
      <li class="serv__list-item">
        <img class="serv__list-item-img" src="@/assets/1.png" />
        <span></span>
        Утримання будинку
      </li>
      <li class="serv__list-item">
        <img class="serv__list-item-img" src="@/assets/4.png" />
        Вода та водовідведення
      </li>
      <li class="serv__list-item">
        <img class="serv__list-item-img" src="@/assets/1.png" /> Газ. Доставка
        газу
      </li>
      <li class="serv__list-item">
        <img class="serv__list-item-img" src="@/assets/1.png" /> Електроенергія
      </li>
    </ul>
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
    list-style: none;
    &-item {
      margin-top: 20px;
      border-radius: 20px;
      font-size: 16px;
      border: solid 2px #b7aeae;
      padding: 10px;
      background: #121ba1;
      color: #ffffff;
      &-img {
        width: 30px;
        padding-right: 10px;
      }
    }
  }
}
</style>
