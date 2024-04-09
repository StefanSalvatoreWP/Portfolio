<template>
  <div id="app">
    <nav class="flex items-center justify-between flex-wrap bg-black p-6">
      <div class="flex items-center flex-shrink-0 text-white mr-6">
        <img
          src="/images/logo.png"
          alt=""
          class="h-10 w-20 mr-2 filter invert brightness-100"
          width="54"
          height="54"
          viewBox="0 0 54 54"
        />
        <span class="font-semibold text-xl tracking-tight"></span>
      </div>
      <div class="w-full lg:w-auto">
        <div class="text-sm lg:flex">
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-white px-4 py-2 rounded-md mr-5 font-bold transition duration-300 ease-in-out hover:bg-white hover:text-black"
            :to="{ path: '/' }"
            active-class="active-link"
          >
            Home
          </router-link>
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-white px-4 py-2 rounded-md mr-5 font-bold transition duration-300 ease-in-out hover:bg-white hover:text-black"
            :to="{ path: '/projects' }"
            active-class="active-link"
          >
            Projects
          </router-link>
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-white px-4 py-2 rounded-md mr-5 font-bold transition duration-300 ease-in-out hover:bg-white hover:text-black"
            :to="{ path: '/contact' }"
            active-class="active-link"
          >
            Contact
          </router-link>
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-white px-4 py-2 rounded-md mr-5 font-bold transition duration-300 ease-in-out hover:bg-white hover:text-black"
            :to="{ path: '/about' }"
            active-class="active-link"
          >
            About
          </router-link>
        </div>
      </div>
      <button
        @click="toggleNavbar"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        :aria-expanded="isNavbarOpen.toString()"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
    </nav>

    <router-view></router-view>
  </div>
  <footer id="foot" class="text-white rounded-lg shadow py-6 text-center">
    <span class="block text-sm text-white sm:text-center dark:text-gray-400"
      >© 2024
      <a href="https://flowbite.com/" class="hover:underline">Portfolio™</a>.
      All Rights Reserved [TOJI].</span
    >
  </footer>
</template>

<script>
export default {
  data() {
    return {
      isNavbarOpen: false,
    }
  },
  methods: {
    toggleNavbar() {
      this.isNavbarOpen = !this.isNavbarOpen
    },
  },
}
</script>

<style scoped>
.active-link {
  border-bottom: 2px solid white;
}
</style>
