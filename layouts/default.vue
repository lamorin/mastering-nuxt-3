<script lang="ts" setup></script>

<template>
  <div class="h-screen flex flex-col justify-between border-2 border-dashed border-lime-700">
    <div class=" border-2 border-dashed border-lime-700">header</div>
    <div class="h-full flex justify-center items-stretch">
      <div class="hidden sm:block min-w-[10rem]  border-2 border-dashed rounded-xl border-lime-700">Chapters</div>
      <slot />
    </div>
    <div class="border-2 border-dashed border-lime-700">footer</div>
  </div>
</template>

<style scoped>

</style>
