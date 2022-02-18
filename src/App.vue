<template>
  <NavBar />

  <div class="h-screen">
    <h1
      class="
        bg-purple-500
        font-bold
        text-4xl
        flex
        justify-center
        items-center
        py-10
        text-purple-200
        transition-all
        bg-gradient-to-r
        from-blue-400
        to-purple-500
      "
    >
      Welcome to Roboticol's website!
    </h1>
    <!-- main body -->
    <div
      class="
        flex flex-col
        space-y-24
        py-10
        justify-center
        bg-gray-50
        mx-52
        my-4
        rounded-xl
        border-2
      "
    >
      <div class="flex flex-row justify-center space-x-20">
        <img
          src="https://i.ytimg.com/vi/eMonGZEB0Ik/maxresdefault.jpg"
          alt="monke"
          class="h-64 border-4 border-purple-400 rounded-lg"
        />
        <p class="w-52">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus
          magna magna, efficitur eget posuere ut, consequat at dui. Sed faucibus
          dolor orci, id facilisis ante bibendum ut. Phasellus et nisi elit.
        </p>
      </div>

      <div class="flex flex-row justify-center space-x-20">
        <p class="w-52">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus
          magna magna, efficitur eget posuere ut, consequat at dui. Sed faucibus
          dolor orci, id facilisis ante bibendum ut. Phasellus et nisi elit.
        </p>

        <img
          src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__480.jpg"
          alt="monke"
          class="h-64 border-4 border-blue-400 rounded-lg"
        />
      </div>
    </div>
  </div>

  <Footer />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Footer,
  },
};
</script>
