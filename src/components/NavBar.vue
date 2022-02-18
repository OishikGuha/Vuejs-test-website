<template>
  <header class="bg-gray-100">
    <div class="px-8 mx-auto">
      <div class="flex justify-around">
        <div class="flex space-x-4">
          <div>
            <!-- logo -->
            <a href="#" class="flex items-center px-2 py-4 font-bold"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 mr-1 text-blue-500"
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
              <span>Oishik Guha's Website</span>
            </a>
          </div>
          <div class="flex items-center space-x-3">
            <a href="#" class="hover:text-gray-500 transition-all">Items</a>
            <a href="#" class="hover:text-gray-500 transition-all">Pricing</a>
          </div>
        </div>
        <div class="flex items-center space-x-3">
          <a href="#" class="hover:text-gray-500 transition-all">Login</a>
          <a
            href="#"
            class="
              py-1
              px-3
              bg-yellow-400
              text-yellow-800
              rounded
              shadow-sm
              hover:shadow-md
              transition-all
            "
            >Signup</a
          >
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
};
</script>