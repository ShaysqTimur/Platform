<script setup>
import headerTitle from './components/headerTitle.vue';
import inputs from './components/inputs.vue';

</script>

<template>
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
    <div class="container-reg">
        <button class="reg-but reg1">Отмена</button>
        <button class="reg-but reg2 ">Сохранить</button>
    </div>
</template>

<style scoped>
.container-reg{
    display: flex;
    background-color: white;
    width: 360px;
    justify-content: end;
    padding: 10px;
}
.reg1{
    color:#DE3A3A ;
}
.reg2{
    color:#3BA9EC ;
}
.reg-but{
    font-weight: 600;
    font-size: 12px;
    border: none;
}
.input-main{
        background: white;
        display: flex;
        width: 360px;
        height: 248px ;
        flex-direction: column ;
    }
</style>
