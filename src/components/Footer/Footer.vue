<template>
  <div>
    <div class="background-green py-12 px-12" style="postion: relative">
      <div class="container mx-auto px-12">
        <div class="grid grid-cols-3">
          <div>
            <img :src="require('@/assets/HomePage/footerlogo.png')" />
            <p
              class="
                py-8
                text-sm
                leading-relaxed
                tracking-wide
                font-regular
                text-white
                font-roboto
                w-72
              "
            >
              Lorem ipsum dolor sit amet,consectetur adipiscing elit. Tincidunt
              facilisis nuncLorem ipsum dolor sit amet, consectetur adipiscing
              elit.
            </p>
          </div>
          <div class="mx-auto">
            <div class="flex flex-col mx-auto">
              <p class="text-lg text-white font-librebaskerville">Sitemap</p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Home
              </p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Visit
              </p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Exhibitions
              </p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Programs & Events
              </p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Store
              </p>
              <p
                class="
                  text-sm
                  leading-loose
                  font-medium
                  tracking-wide
                  text-white
                  font-roboto
                "
              >
                Membership
              </p>
            </div>
          </div>
          <div class="mx-auto">
            <div class="flex flex-col mx-auto">
              <p class="text-lg text-white font-librebaskerville">Connect</p>
              <img
                :src="require('@/assets/HomePage/Frame 15.png')"
                class="py-2"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="background-darkgreen mx-auto">
      <p class=" font-roboto text-white text-sm py-8 font-regular text-center">
        © 2021 Mist Gardens. All rights reserved.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.background-green {
  background-color: #414840;
}
.background-darkgreen {
  background-color: #343d33;
}
.img-1 {
  position: absolute;
  left: 60%;
  top: 1200px;
}
.img-2 {
  height: auto;
}
</style>
