<template>
  <div class="container mx-auto py-12 px-12">
    <div class="flex flex-row">
      <p
        class="
          flex-auto
          text-5xl text-customh1
          py-6
          font-librebaskerville
          leading-tight
          my-auto
        "
      >
        News & Updates
      </p>
      <p
        class="
          text-sm text-customh1
          py-6
          font-roboto font-bold
          tracking-morewider
          my-auto
        "
      >
        VIEW ALL POSTS
      </p>
    </div>
    <hr class="border-custom border-2 border-custom-dark opacity-40" />
    <div class="py-12 grid grid-cols-2 gap-8">
      <div>
        <div class="flex flex-col">
          <img
            :src="require('@/assets/HomePage/Rectangle 24.png')"
            class="w-full"
          />
          <div class="flex flex-col mx-6 my-6">
          <p class="font-librebaskerville type-color text-3xl">Plants Around Us</p>
          <p class="font-roboto type-color text-lg py-4 leading-relaxed">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit.Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
          <p class="font-roboto type-color italic text-lg">December 23, 2021</p>
        </div>
        </div>
      </div>
      <div class="grid grid-rows-3 gap-4">
        <div class="flex flex-row gap-4">
          <div class="flex-1">
            <img
              :src="require('@/assets/HomePage/blog1.png')"
              class="img-1"
            />
            
          </div>
          <div class="flex-1 my-auto">
              <p class="font-librebaskerville type-color text-2xl tracking-wide">Lush Gardens</p>
              <p class="font-roboto type-color text-lg font-normal tracking-wide py-4">Lorem ipsum dolor sit amet, consectetur donec adipiscing elit. Tincidunt facilisis nunc lorem </p>
              <p class="font-roboto type-color italic text-lg">December 23, 2021</p>
          </div>
        </div>
        <div class="flex flex-row gap-4">
          <div class="flex-1">
            <img
              :src="require('@/assets/HomePage/blog2.png')"
              class="img-1"
            />
            
          </div>
          <div class="flex-1 my-auto">
              <p class="font-librebaskerville type-color text-2xl tracking-wide">Exotic Nature</p>
              <p class="font-roboto type-color text-lg font-normal tracking-wide py-4">Lorem ipsum dolor sit amet, consectetur donec adipiscing elit. Tincidunt facilisis nunc lorem </p>
              <p class="font-roboto type-color italic text-lg">December 23, 2021</p>
          </div>
        </div>
        <div class="flex flex-row gap-4">
          <div class="flex-1">
            <img
              :src="require('@/assets/HomePage/blog3.png')"
              class="img-1"
            />
            
          </div>
          <div class="flex-1 my-auto">
              <p class="font-librebaskerville type-color text-2xl tracking-wide">It Starts with Soil</p>
              <p class="font-roboto type-color text-lg font-normal tracking-wide py-4">Lorem ipsum dolor sit amet, consectetur donec adipiscing elit. Tincidunt facilisis nunc lorem </p>
              <p class="font-roboto type-color italic text-lg">December 23, 2021</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.button-color {
  background-color: #475f45;
}
.type-color {
    color : #475F45;

}
.img-1 {
     height: 218px;
  width: 100%;
  object-fit: cover;
 }
</style>
