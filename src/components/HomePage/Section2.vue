<template>
<div class="background-green py-12 px-12"  style="postion:relative;">
  <div class="container mx-auto py-12 px-12">
      <img :src="require('@/assets/HomePage/Frame.png')" alt="logo" class="img-1" />
      <div class="grid grid-cols-2">
          <div class="mx-auto">
              <img :src="require('@/assets/HomePage/Rectangle 21.png')" class="img-2"/>
          </div>
          <div class="mx-24 my-auto">
              <p class="text-5xl text-white font-librebaskerville leading-tight">Discover Yourself With Nature</p>
              <p class="text-xl font-normal mt-6 font-roboto leading-relaxed text-white ">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nunc</p>
              <div class="my-6">
                  <button class="bg-transparent text-white border-2 border-white hover:bg-white hover:text-custom px-12 py-4">
                      <p class="text-sm font-bold  font-roboto tracking-morewider">LEARN MORE</p>
                  </button>
              </div>
          </div>
          
      </div>
      <div class="pt-20 grid grid-cols-1">
          <div class="mx-24">
              <img :src="require('@/assets/HomePage/Rectangle 22.png')" class="w-full"/>
          </div>
      </div>
  </div>
</div>
</template>

<script>
export default {};
</script>

<style scoped>
.background-green {
background-color: #343D33;
}
.img-1 {
position: absolute;
left:60%;
top: 1200px;
}
.img-2 {
    height: auto;
}
</style>
