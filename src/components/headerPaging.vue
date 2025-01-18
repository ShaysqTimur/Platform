<script setup>

defineProps({
  pagingName: {
    type: String,
    required: true
  }
});
</script>

<template>
        <div class="scroll-menu">
            <img src="../assets/Iphone13promax.png" alt="Image" class="scroll-img"/>
            <p class="scroll-name">{{ pagingName }}</p>
        </div>
   
</template>

<style scoped>
    .scroll-img{
        min-width: 100px;;
    }
    .scroll-menu{
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 97px;
    }
    .scroll-name{
        font-weight: 600;
        font-size:10px;
        color: black;
        text-align: center;
        padding: 10px;
    }
</style>