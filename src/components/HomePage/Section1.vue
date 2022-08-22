<template>
<div class="container mx-auto py-12 px-12">
  <div class="grid grid-cols-2">
    <div class="my-auto mx-20">
      <p class="text-6xl text-customh1 font-librebaskerville leading-tight">A Beautiful</p>
      <p class="text-6xl text-customh1 font-librebaskerville leading-tight">Adventure Awaits</p>
      <p class="text-2xl font-light font-roboto leading-relaxed">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nunc</p>
      <div class="flex flex-row gap-4 my-6">
      <button class="button-color hover:bg-white text-white  hover:text-custom px-12 py-4">
        <p class="text-sm font-bold font-roboto tracking-morewider">BUY TICKETS</p>
      </button>
      <button class="border-2 border-custom text-custom hover:bg-buttoncolor hover:border-white hover:text-white px-12 py-4">
        <p class="text-sm font-bold  font-roboto tracking-morewider">LEARN MORE</p>
      </button>
      
      </div>
    </div>
    <div class="mx-auto">
      <img :src="require('@/assets/HomePage/Group 5.png')" alt="logo" class="" />
    </div>
  </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.button-color {
background-color: #475F45;

}
</style>
