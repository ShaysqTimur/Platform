<script setup>
    defineProps({
    setName: {
        type: String,
        required: true
    },
    setTitle: {
        type: String,
        required: true
    },
    setBut: {
        type: String,
        required: true
    },
    
})
</script>

<template>
    <div class="set-main">
        <div class="set-box">
            <p class="set-title">{{ setTitle }}</p>
            <h1 class="set-name">{{ setName }}</h1>
        </div>
        <button class="set-but">{{ setBut }}</button>
    </div>
</template>

<style scoped>
    .set-but{
        font-weight: 600;
        font-size: 12px;
        color: #3BA9EC;
        border: none;
    }
    .set-main{
        padding: 10px;
        display: flex;
        width: 360px;
        background-color: white;
        justify-content: space-between;
    }
    .set-title{
        font-weight:  600;
        font-size: 12px;
        color: black;
    }
    .set-name{
        font-weight: 600;
        font-size:10px;
        color: #868686;
    }
</style>