<script setup>
import card from './components/card.vue';
import headerTitle from './components/headerTitle.vue';
import inputs from './components/inputs.vue';
import infoGeo from './components/infoGeo.vue';
import add from './components/add.vue';
import titleTitle from './components/titleTitle.vue';
import checkbox from './components/checkbox.vue';
import container from './components/container.vue';
import cardTabs from './components/cardTabs.vue';
import money from './components/money.vue';
import headerPaging from './components/headerPaging.vue';
import headerTwo from './components/headerTwo.vue';
import svaiper from './components/svaiper.vue';
import { ref } from 'vue';
const cards = ref ([
        {titleName:"Чехол Iphone 13 Pro Max"},
        {cardsTitle:"Электроника"},
        {cardsPrice:"1250₸"},
        {headerName:"Популярные"},
        {headerTitle:"Посмотреть"},
        {inputTitle:"Номер телефона"},
        {inputLabel:"Введите номер телефона"}

    ])
</script>
  
<template>
  <svaiper/>
<div class="main-scroll">
    <headerTitle
        header-name="Категории"
        header-title="Посмотреть"
    />
    <div class="menu-scroll">
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
      <headerPaging
        paging-name="Электроника"
      /> 
    

    </div>  
 
</div>
  <headerTitle
      header-name = "Популярные" 
      header-title = "Посмотреть"
  />
  <div class="card-main">
    <div class="card-section">
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
    </div>
    <div class="card-section">
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
    </div>
    <div class="card-section">
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
    </div>
    <div class="card-section">
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
      <card
        cards-name = "Iphone 13 Pro Max"
        cards-title = "Электроника"
        cards-Price = "1250₸"
        cards-ranking = "4.8"
      />
    </div>
  </div>
  
  
    
 

</template>

<style scoped>
    .main-scroll{
      border-bottom: 1px solid #00000059 ;
      padding-bottom:5px ;
    }
    .menu-scroll{
      display: flex;
      overflow: scroll;
      background-color: white;
      width: 360px;
    }
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
      border-bottom: 1px solid #00000059 ;
      
    }
    .card-main{
      display: flex;
      justify-content: space-between;
      flex-direction: column;
      border-bottom: 1px solid #00000059 ;

      
    }
</style>
