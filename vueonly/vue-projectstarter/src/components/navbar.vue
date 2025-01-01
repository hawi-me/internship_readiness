<script setup>
import logo from '../assets/logo5.png'
import {ref} from 'vue';
const link = ref('https://cdn.icon-icons.com/icons2/2648/PNG/512/logo_freelancer_com_icon_160826.png')

</script>
<template>
    <nav class="bg-green-700 border-b border-green-500">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="flex h-20 items-center justify-between"> 
        <div class="flex flex-1 items-center justify-center md:items-stretch md:justify-start"> 
          <a class="flex flex-shrin-0 items-center mr-4" href="index.html">
            <img class="h-10 w-auto" v-bind:src="link" alt="Vue Jobs" />
            <span class="hidden md:block text-white text-2xl font-bold ml-2"> Frontend Freelancers</span>
          </a>
          <div class="md:ml-auto">
            <div class="flex space-x-2">
                <a href="index.html" class="text-white br-green-900 hover:bg-grey-900 hover:text-white rounded-md px-3 py-2">
                    Home
                </a>
                <a href="index.html" class="text-white br-green-900 hover:bg-grey-900 hover:text-white rounded-md px-3 py-2">
                    jobs
                </a>
                <a href="index.html" class="text-white br-green-900 hover:bg-grey-900 hover:text-white rounded-md px-3 py-2">
                    Add Jobs 
                </a>
            </div>


          </div>
        </div>
          </div>
    
      </div>
    
    </nav>
     
    </template>
    
<style>

</style>