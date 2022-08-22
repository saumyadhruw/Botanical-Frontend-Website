<template>
  <nav class="container mx-auto py-6 mx-12">
    <div class="flex flex-row">
      <img :src="require('@/assets/logo.png')" alt="logo" />
      <div class="flex flex-row flex-1 gap-8 justify-end my-auto">
        <button
          class="font-roboto font-semibold color-text text-sm tracking-morewider px-4 py-2"
          href="#"
        >
          HOME
        </button>
        <button
          class="font-roboto font-semibold color-text text-sm tracking-morewider px-4 py-2"
          href="#"
        >
          VISIT
        </button>
        <button
          class="font-roboto font-semibold color-text text-sm tracking-morewider px-4 py-2"
          href="#"
        >
          EXHIBITIONS
        </button>
        <button
          class="font-roboto font-semibold color-text text-sm tracking-morewider px-4 py-2"
          href="#"
        >
          PROGRAMS & EVENTS
        </button>
        <button
          class="font-roboto font-semibold color-text text-sm tracking-morewider px-4 py-2"
          href="#"
        >
          STORE
        </button>
        <button
          class="font-roboto font-semibold border-2 color-border text-sm tracking-morewider mx-4 px-6 py-3 hover:border-white hover:text-white hover:bg-custom"
          href="#"
        >
          MEMBERSHIP
        </button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.color-text {
  color: #414840;
}
.color-border {
  border-color: #414840;
}
.color-bg {
  color: #414840;
}
</style>
