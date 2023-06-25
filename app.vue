<template>
  <div class="m-auto max-w-[960px]">
    <nav class="flex gap-2">
      <NuxtLink class="underline text-blue-600" to="/"
        >Server Rendered (Works)</NuxtLink
      >
      <NuxtLink class="underline text-blue-600" to="/spa"
        >Client Rendered (Broken)</NuxtLink
      >
    </nav>
    <NuxtPage />

    <div class="bg-gray-600 mt-10 rounded p-6 text-white">
      ⚠️ NOTE: This only affects the built project (everything works in dev)
    </div>
  </div>
</template>
