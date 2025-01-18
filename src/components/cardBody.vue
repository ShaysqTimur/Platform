<script setup>
    defineProps({
    cardBackground:{
        type:String,
        required:true 
  }
 
})
</script>
<template>
    <div class="card-body">
        {{ cardBackground }}
    </div>
</template>

<style scoped>
    .card-body{
        width: 100%;
        padding: 10px;
        background: white;

    }
</style>