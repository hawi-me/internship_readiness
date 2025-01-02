<script setup >
import navbar from './components/navbar.vue';
import Herosection from './components/Herosection.vue';
// import {ref} from 'vue';

//   const name = ref('vue3');
//   const age = ref('20');
//   const task = ref(['vue3', 'vue2', 'vue1']);
//   const addTask = () => {
//     task.value.push(name.value);
//     name.value = '';
//   };
  
//   const newTask = ref('');

  
 
  


</script>

<template>
<div>
    <navbar></navbar>
    <Herosection title="this is title"></Herosection>
    <h1 class='text-4xl font-extrabold text-white sm:text-5xl md:text-6xl'>
  {{ title }}
</h1>

</div>
  
</template>

<style scoped>

</style>
