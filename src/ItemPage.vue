<script setup>
import cardTabs from './components/cardTabs.vue';
import headerTitle from './components/headerTitle.vue';
import card from './components/card.vue';
import box from './components/box.vue';
</script>

<template>
    <box/>
    
     <cardTabs
         tab-name="Подробнее"
         tab-title="Характеристики"
         tab-text="Xtreon XT2453DE - это высококачественный монитор, разработанный для удовлетворения потребностей как профессиональных пользователей, так и геймеров."
         tab-comment="Отзывы"
    />

    <headerTitle
        header-name="Похожие товары"
        header-title="Посмотреть"
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
    .card-section{
      display: flex;
      border-bottom: 1px solid #00000059 ;
      
    }
    .card-main{
      display: flex;
      justify-content: space-between;
      flex-direction: column;

      
    }

</style>