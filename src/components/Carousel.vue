<script setup>
import headerTitle from './headerTitle.vue';
defineProps({
  carouselTitle: {
    type: String,
    required: false
  }
});
</script>
<template>
    <headerTitle    
        header-name="Категория"
        header-title="Посмотреть"
    />
    <div class="main-cor">
        <div class="carousel-img">
        <img src="../assets/Iphone13promax.png" alt="Image" class="cards-img" width="71px" height="88px"/>
    </div>
    <div class="carousel-title">
        <p class="carousel-text">{{ carouselTitle }}</p>
    </div>
    </div>
    
</template>
<style scoped>
    .main-cor{
        display: flex;
        justify-content: center;
        flex-direction: column;
    }
    .carousel-title{
        width: 67px;
        height: 14px;

    }
    .carousel-text{
        font-weight: 600;
        font-size: 10;
        color: black;
    }
</style>