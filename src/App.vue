<script setup>

</script>

<template>
  <h1 class="text-xs sm:text-sm md:text-base lg:text-lg xl:text-xl border-vuejs-900 border-2">
    Hello world!
  </h1>

  <div class="whitespace-nowrap">
    <h1 class="text-9xl underline decoration-red-500 decoration-dotted decoration-8">Title 1</h1>
    <h2 class="text-2xl">Title 2</h2>
    <h3 class="text-xl">Title 3</h3>
    <p> Test truncate text truncate text truncate text truncate text truncate text truncate text truncate text truncate text</p>
    <p class="truncate" style="width: 200px;"> Test truncate text truncate text truncate text truncate text truncate text truncate text truncate text truncate text</p>
  </div>

  <div class="bg-red-500 p-4">
    Hello
  </div>

  <div class="flex w-full space-x-2 bg-white-300 min-h-screen">
    <div class="w-1/5 bg-indigo-500 ">Side bar</div>
    <div class="w-4/5  bg-green-500">Main content</div>
  </div>
</template>