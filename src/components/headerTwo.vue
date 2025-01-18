<script setup>
    defineProps({
    twoName: {
    type: String,
    required: true
  },
    twoTitle: {
    type: String,
    required: false
  }
});
</script>

<template>
    <div class="main">
        <div class="header">
            <p class="header-text"><svg xmlns="http://www.w3.org/2000/svg" class="Two-icons" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>{{ twoName }}</p>
        </div>
        <div class="header-but">
            <button class="cart">{{ twoTitle}}</button>
        </div>
        
    </div>
</template>

<style scoped>
    .header-but{
        display: flex;
        justify-content: center;
    }
    .cart{
        text-align: center;
        border-radius:12px ;
        background-color: #3BA9EC;
        color: white;
        border: none;
        cursor: pointer;
        font-size: 10px;
        font-weight: 600;
    }
    .main{
        display: flex;
        background-color: white;
        justify-content: space-between;
        width: 340px;
    }
    .header{
        display: flex;
       
    }
    .header-text{
        font-weight:600 ;
        font-size: 20px;
        color: black;
    }
    .Two-icons{
        width: 15px;
        height: 15px;
        color:#3BA9EC ;
    }

</style>