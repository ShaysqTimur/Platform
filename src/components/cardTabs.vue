<script setup>
import infoGeo from './infoGeo.vue';
import comm from './comm.vue';
    defineProps({
    tabName: {
        type: String,
        required: true
    },
    tabTitle: {
        type: String,
        required: true
    },
    tabText: {
        type: String,
        required: true
    },
    tabComment: {
        type: String,
        required: true
    }
    
})

    function Toggle(itemId){
        document.getElementById(itemId).classList.add('invisible');
        console.log("giiggg");
    }
    function toggleDelete(itemId){
         document.getElementById(itemId).classList.remove('invisible');
    }   
   
</script>

<template>
    <div class="tab-main">
        <div class="tab-header">
            <button class="tab-but" @click="Toggle('content2'),Toggle('content3'),toggleDelete('content1')">
                {{ tabName }}
            </button>
            <button class="tab-but" @click="Toggle('content1'),Toggle('content3'),toggleDelete('content2')" >
                {{ tabTitle }}
            </button>
            <button class="tab-but" @click="Toggle('content1'),Toggle('content2'),toggleDelete('content3')">
                {{ tabComment }}
            </button>
        </div>
        <div id="content1"   class="tab-text">{{tabText}}</div>
        <div id="content2" class="tab-text  tab-column invisible"> 
            <infoGeo
                infoName = "Частота кадров:"
                infoTitle = "144гц"
            />
            <infoGeo
                infoName = "Пиксели:"
                infoTitle = "1920х1080"
            />
            <infoGeo
                infoName = "Какая-то залупа:"
                infoTitle = "Точно такая-же залупа"
            />
        </div>
        <div id="content3" class=" tab-text tab-com invisible">
            <comm
                comName="Данил"
                comTitle="08.08.2008"
                tab-texts="Xtreon XT2453DE - это высококачественный монитор, разработанный для удовлетворения потребностей как профессиональных пользователей, так и геймеров."
            />
        </div>
    </div>

</template>

<style scoped>
    .tab-text{
        font-size: 10px !important;
        padding: 10px;
    }
    .tab-com{
        display: flex;
        flex-direction: column;
    }
    .tab-column{
        display: flex;
        flex-direction: column;
    }
    .invisible{
        display: none !important;
    }
    .tab-main{
        display: flex;
        flex-direction: column;
        width: 360px;
        background-color: white;
        padding-bottom: 10px;
        border-bottom: 1px solid #00000059 ;
    }
    .tab-header{
        display: flex;
        justify-content: space-evenly;
        width: 340px;
        height: 26px;
    }
    .tab-but.active {
        color: #3BA9EC;
        border-bottom: 2px solid #3BA9EC;
    }
    .tab-but{
        color:#868686 ;
        font-weight: 600;
        font-size: 12px;
        cursor: pointer;
        border: none;
    }
    .tab-but:hover{
        color: #3BA9EC;
        border-color:#3BA9EC ;
        border-bottom: 1px;
    }
</style>