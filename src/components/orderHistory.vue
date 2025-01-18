<script setup>
defineProps({
  orderName:{
    type:String,
    required:true 
  },
  orderDate:{
    type:String,
    required:true 
  }
})
</script>

<template>
  <div class="order"> 
      <div class="order-details">
        <div class="order-block">
            <h1 class="order-text-h1"> Заказ{{ orderName }}</h1>
            <h2 class="order-text-h2">{{ orderDate }}</h2>
        </div>
        <div class="order-button">
            <button class="order-but1">Детали заказа</button>
        </div>

      </div>

  </div>
</template>

<style scoped>
   
  .order{
    padding: 10px;
    width:100%;
    height: 191px;
    color: black;
  }
 
  .order-details{
    margin-bottom: 65px;
    display: flex;
    justify-content: space-between;
    align-items: start;
    width: 340px;
    height: 62px;
  }
  .order-button{
   cursor: pointer;
   border: none;
  }.order-but1{
    text-align: center;
    font-weight: 600;
    font-size: 12px;
    color: #3BA9EC;
    border: none;
    
    
  }
  .order-but1:hover{
    border: none;
  }

  .order-text-h1{
    font-weight: 600;
    font-size: 12px;
    
  }
  .order-text-h2{
    font-weight: 600;
    font-size: 10px;
    color:#868686 ;
    
  }

</style>
