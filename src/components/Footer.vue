<template>
  <footer class="bg-gray-100">
    <div class="py-5 flex flex-row justify-center space-x-10">
      <!-- logo -->
      <div class="flex flex-col my-3 items-center">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-20 w-20 text-blue-500"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"
          />
        </svg>
        <h1 class="font font-semibold">Oishik Guha&trade;</h1>
      </div>

      <!-- list -->
      <div class="flex flex-row justify-center space-x-10 py-5">
        <ul class="flex flex-col leading-7">
          <a href="#" class="hover:underline transition-all">What I do</a>
          <a href="#" class="hover:underline transition-all">About me</a>
          <a href="#" class="hover:underline transition-all">Other stuff</a>
        </ul>
        <ul class="flex flex-col leading-7">
          <a href="#" class="hover:underline transition-all">Shop</a>
          <a href="#" class="hover:underline transition-all">Contests</a>
          <a href="#" class="hover:underline transition-all">I forgor</a>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
