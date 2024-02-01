<template>
  <div class="card">
    <div class="card-image rounded-xl overflow-hidden">
      <img src="../iamges/icons-preview.png" alt="" srcset="" />
    </div>
    <p class="card-title">应用统一图标</p>
    <p class="card-body">
        目前已包含89个图标, 后续会不断更新, 包括热门和冷门的图标。512*512像素, 支持PNG格式。
    </p>
  </div>
</template>

<script setup lang="ts">
// import IconsPreview from "../iamges/icons-preview.png"
</script>
<style scoped>
.card {
  padding: 20px;
  width: 330px;
  min-height: 370px;
  border-radius: 20px;
  background: #e8e8e8;
  box-shadow: 5px 5px 6px #dadada, -5px -5px 6px #f6f6f6;
  transition: 0.4s;
}

.card:hover {
  translate: 0 -10px;
}

.card-title {
  font-size: 18px;
  font-weight: 600;
  color: #2e54a7;
  margin: 15px 0 0 10px;
}

.card-image {
  min-height: 170px;
  background-color: #c9c9c9;
  border-radius: 15px;
  box-shadow: inset 8px 8px 10px #c3c3c3, inset -8px -8px 10px #cfcfcf;
}

.card-body {
  margin: 13px 0 0 10px;
  color: rgb(31, 31, 31);
  font-size: 15px;
}

</style>
