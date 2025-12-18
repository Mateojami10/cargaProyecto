<template>
    <div class="view-container">
        <JuegoCasino/>
    </div>
  
</template>

<script>
import JuegoCasino from '@/components/JuegoCasino.vue';

export default {
    components: {
        JuegoCasino
    }
}
</script>

<style scoped>

.view-container {
    display: flex;
    justify-content: center;
    align-items: center;
    border: 2px solid black;
   
}

</style>