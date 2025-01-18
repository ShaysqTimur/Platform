<script setup>
    defineProps(['titleName'])
</script>
<template>
    <h1 class="card-text">{{ titleName }}</h1>
</template>
<style scoped>
     .order-text{
        font-weight: 600;
        font-size: 20px;
        width: 171px;
        gap: 5px;
        text-align: left;
  }
</style>