<script setup>
import money from './components/money.vue';
import inputs from './components/inputs.vue';
import headerTitle from './components/headerTitle.vue';
import historyTitle from './components/historyTitle.vue';
</script>

<template>
    <money
         money-name="1,23"
         money-title="Как получить бонусы?"
    />
    <div class="input-main">
      <headerTitle
        header-name = "Данные аккаунта" 
        header-title = "Посмотреть"
      />
      <inputs
        inputLabel = "Введите номер телефона"
        inputTitle = "Номер телефона"
      />
      <inputs
        inputLabel = "Введите ФИО"
        inputTitle = "Имя пользователя"
      />
      <inputs
        inputLabel = "Введите адрес доставки"
        inputTitle = "Адрес доставки"
      />
  </div>
  <headerTitle
    header-name="История Заказов"
  />
  <historyTitle
    set-title="Заказ#123567890"
    set-name="12 сентября 2024 год"
    set-but="Детали заказа"
  />

</template>
    
<style scoped>
.input-main{
        background: white;
        display: flex;
        width: 360px;
        height: 248px ;
        flex-direction: column ;
    }
</style>