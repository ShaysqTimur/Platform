<script setup>
import inputs from './components/inputs.vue';
import infoGeo from './components/infoGeo.vue';
import cardTabs from './components/cardTabs.vue';
import container from './components/container.vue';
import money from './components/money.vue';
import headerTwo from './components/headerTwo.vue';
import headerTitle from './components/headerTitle.vue';
import checkbox from './components/checkbox.vue';
import titleTitle from './components/titleTitle.vue';
import headerThree from './components/headerThree.vue';
</script>

<template>
  <headerThree
    two-name="Корзина"
    two-title="Выбрать всё"
    three-title="Удалить(999)"
  />
  <div class="box">
    <div class="box-cont1">
      <div class="checbox">
        <checkbox/>
      </div>
      <container
        container-name="Монитор XTREON XT2453DE"
        container-title="Электроника"
        ontainer-quantity="(228)"
      />
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icons-box">
      <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0" />
      </svg>

    </div>
    <div class="box-cont2">
      <titleTitle
        title-names="50 999₸"
        title-title="С 999шт * 999₸/шт"
      />
      <add
        count="1 шт"
      />
    </div>
  </div>
  <div class="box">
    <div class="box-cont1">
      <div class="checbox">
        <checkbox/>
      </div>
      <container
        container-name="Монитор XTREON XT2453DE"
        container-title="Электроника"
        ontainer-quantity="(228)"
      />
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icons-box">
      <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0" />
      </svg>

    </div>
    <div class="box-cont2">
      <titleTitle
        title-names="50 999₸"
        title-title="С 999шт * 999₸/шт"
      />
      <add
        count="1 шт"
      />
    </div>
  </div>

    <div class="box">
    <div class="box-cont1">
      <div class="checbox">
        <checkbox/>
      </div>
      <container
        container-name="Монитор XTREON XT2453DE"
        container-title="Электроника"
        ontainer-quantity="(228)"
      />
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icons-box">
      <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0" />
      </svg>

    </div>
    <div class="box-cont2">
      <titleTitle
        title-names="50 999₸"
        title-title="С 999шт * 999₸/шт"
      />
      <add
        count="1 шт"
      />
    </div>
  </div>


 <headerTitle
        header-name = "Похожие товары" 
        header-title = "Посмотреть"
  />
  <div class="box">
    <div class="box-cont1">
      <div class="checbox">
        <checkbox/>
      </div>
      <container
        container-name="Монитор XTREON XT2453DE"
        container-title="Электроника"
        ontainer-quantity="(228)"
      />
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="icons-box">
      <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0" />
      </svg>

    </div>
    <div class="box-cont2">
      <titleTitle
        title-names="50 999₸"
        title-title="С 999шт * 999₸/шт"
      />
      <add
        count="1 шт"
      />
    </div>
  </div>
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
  <div class="info">
    <headerTitle
        header-name = "Оплата" 
    />
        <infoGeo
          infoName = "Вид оплаты:"
          infoTitle = "При получении"
        />
          <infoGeo
            infoName = "Товары:"
            infoTitle = "49 000₸"
          />
          <infoGeo
            infoName = "Доставка:"
            infoTitle = "Бесплатно"
          />
          <infoGeo
            infoName = "Итого:"
            infoTitle = "49 000₸"
          />
  </div>
  <div class="info">
    <headerTitle
        header-name = "Самовывоз" 
    />
        <infoGeo 
          infoName = "Время работы склада:"
          infoTitle = "9:00 - 19:00"
        />
          <infoGeo 
            infoName = "Время прибытие товара:"
            infoTitle = "21 сетября, 13:12"
          />
          <infoGeo 
            infoName = "Адрес склада:"
            infoTitle  = "Ул.Пушкина 24/2" 
            isBlue = "true"
          />
  </div>
  
  <headerTwo
    two-name="Товары"
    two-title="Выбрать все"
  />
  
</template>

<style scoped> 
  .checbox{
      display: flex;
      justify-content: center;
      align-items: center
    }

    .icons-box{
      width: 20px;
      height: 20px;
      color:#B7B7B7 ;
      border: 1.5px;
    }
    .box-cont2{
      padding: 5px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 340px;
    } 
    .box-cont1{
      width: 340px;
      padding: 5px;
      display: flex;
      justify-content: space-between;
  
    }
.box{
      width: 360px;
      height: 168px;
      background-color: white;
      display:flex;
      align-items: center;
      flex-direction: column;
    }
    .info{
      padding: 10px;
      display: flex;
      flex-direction: column;
      width: 340px;
      background: white;
    }
    .info-container{
      display: flex;
      justify-content: space-between;
      flex-direction: row;
    }
    .input-main{
        background: white;
        display: flex;
        width: 360px;
        height: 248px ;
        flex-direction: column ;
    }
    .card-section{
      display: flex;
      
    }
    .card-main{
      display: flex;
      justify-content: space-between;
      flex-direction: column;

      
    }

</style>