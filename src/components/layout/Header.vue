<template>
  <div class="header flex">
    <div class="right">서주의 쇼핑몰</div>
    <div class="flex">
      <div class="item">로그인</div>
      <div class="item">SALE</div>
      <div class="item">의류</div>
      <div class="item">가구</div>
      <div class="item">식품</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
.header {
  width: 100%;
  background-color: navajowhite;
  padding: 10px;
}

.flex {
  display: flex;
  justify-content: space-between;
}

.item {
  padding: 0 4px;
}
</style>
