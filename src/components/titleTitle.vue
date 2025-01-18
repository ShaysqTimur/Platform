<script setup>
defineProps({
    titleNames: {
        type: String,
        required: true
  },
    titleTitle: {
        type: String,
        required: true
  },

})
</script>

<template>
    <div class="title">
        <p class="title-name">{{ titleNames }}</p>
        <h1 class="title-title"> {{ titleTitle }}</h1>
    </div>
</template>

<style scoped>
    .title{
        width: 73px;
        height: 28px;
        background-color: white;
        display: flex;
        flex-direction: column;
       
    }
    .title-name{
        font-weight: 600;
        font-size: 10px;
    }
    .title-title{
        font-weight: 400;
        font-size: 8px;
        color: #868686;
    }
</style>