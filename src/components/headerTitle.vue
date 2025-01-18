<script setup>
defineProps({
  headerName: {
    type: String,
    required: true
  },
  headerTitle: {
    type: String,
    required: false
  }
});
</script>

<template>
  <div class="header-main">
    <div class="header-names">
      <p class="header-text">{{ headerName }}</p>
    </div>
    <div class="header-titles">
      <button class="but-title">
        {{ headerTitle }}
      </button>
    </div>
  </div>
</template>

<style scoped>
.header-main {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 30px;
  background-color: white;
  width: 360px;
}
.header-names{
  padding: 10px;
}
.header-text {
  font-weight: 600;
  font-size: 20px;
  text-align: center;
  padding-top: 5px;
}
.but-title {
  font-weight: 600;
  font-size: 10px;
  color: #3ba9ec;
  cursor: pointer;
  border: none;
  background-color: white;
}
</style>
