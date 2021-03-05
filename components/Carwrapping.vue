<template>
  <div class="flex flex-row car__animation">
    <div class="bg-indigo-900 font-sans">
      <img src="@/assets/images/caropaque.png" alt="3M Preferred" />
      <div class="flex flex-col p-20 text-white">
        <div class="text-4xl">CAR WRAPPING</div>
        <span class="text-gray-400">Identity and Protection</span>
      </div>
    </div>
    <div class="change__color">
      <img src="@/assets/images/cartransparent2.png" alt="3M Preferred" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Carwrapping',
}
</script>
<style>
.change__color:hover {
  background-color: rgba(49, 46, 129, var(--tw-bg-opacity));
}
</style>
