<template>
  <!-- component -->
  <div class="w-full min-h-screen flex items-center justify-center bg-black">
    <div class="md:w-2/3 w-full px-4 text-white flex flex-col">
      <div class="w-full text-7xl font-bold">
        <h1 class="w-full md:w-2/3">How can we help you?. get in touch</h1>
      </div>
      <div class="flex mt-8 flex-col md:flex-row md:justify-between">
        <p class="w-full md:w-2/3 text-gray-200">
          To ensure that all Wikipedia content is verifiable, anyone may question an
          uncited claim. If your work has been tagged.
        </p>
        <div class="w-44 pt-6 md:pt-0">
          <a
            class="bg-red-500 justify-center text-center rounded-lg shadow px-10 py-3 flex items-center"
            ><button>Contact US</button></a
          >
        </div>
      </div>
      <div class="flex flex-col">
        <div class="flex mt-24 mb-10 flex-row justify-between">
          <div class="">
            <h3 class="italic uppercase font-mono font-extrabold text-white">
              Franc_Pro
            </h3>
          </div>
          <a
            class="hidden md:block cursor-pointer text-gray-400 hover:text-black uppercase"
            >About</a
          >
          <a
            class="hidden md:block cursor-pointer text-gray-400 hover:text-black uppercase"
            >Services</a
          >
          <a
            class="hidden md:block cursor-pointer text-gray-400 hover:text-black uppercase"
            >Songs</a
          >
          <a
            class="hidden md:block cursor-pointer text-gray-400 hover:text-black uppercase"
            >login</a
          >
          <div class="flex flex-row space-x-8 items-center justify-between">
            <a href="#">
              <!-- Facebook -->
              <font-awesome-icon :icon="['fab', 'facebook']" class="text-white h-6 w-6" />
            </a>
            <a href="#">
              <!-- Github -->
              <font-awesome-icon :icon="['fab', 'github']" class="text-white h-6 w-6" />
            </a>
            <a href="#">
              <!-- Twitter -->
              <font-awesome-icon :icon="['fab', 'twitter']" class="text-white h-6 w-6" />
            </a>
            <a href="#">
              <!-- Twitter -->
              <font-awesome-icon
                :icon="['fab', 'linkedin-in']"
                class="text-white h-6 w-6"
              />
            </a>
          </div>
        </div>
        <hr class="border-gray-600" />
        <p class="w-full text-center my-1 text-gray-300">
          Copyright © 2022 Church of Elohim.Kenya
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
