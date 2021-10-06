<template>

<div class="w-full h-screen justify-center items-center">
<div class="grid grid-cols-8">
  <NuxtLogo/>
</div>
  <p class="text-red-500 font-bold"> {{title}} </p>

  <router-link to="/about">About</router-link>
</div>
  
  
</template>

<script>
// import NuxtLogo from '/components/NuxtLogo.vue'
export default {
  data() {
      return {
        title: 'Home page'
      }
    },
   head: {
    title: 'Home page',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Home page description'
      }
    ],
  }
  
}

</script>
