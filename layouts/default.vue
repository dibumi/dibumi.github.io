<script setup lang="ts">

</script>

<template>
  <header class="max-w-7xl mx-auto">
    <nav class="bg-white border-gray-200 dark:bg-gray-900 text-md">
      <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
<!--        <a href="https://flowbite.com/" class="flex items-center">-->
<!--          <img src="https://flowbite.com/docs/images/logo.svg" class="h-8 mr-3" alt="Flowbite Logo"/>-->
          <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">DiBumi</span>
<!--        </a>-->
        <button data-collapse-toggle="navbar-default" type="button"
                class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                aria-controls="navbar-default" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M1 1h15M1 7h15M1 13h15"/>
          </svg>
        </button>
        <div class="hidden w-full md:block md:w-auto" id="navbar-default">
          <ul class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
            <li>
              <a href="#"
                 class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white md:dark:text-blue-500"
                 aria-current="page">Home</a>
            </li>
            <li>
              <a href="#"
                 class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Portofolio</a>
            </li>
            <li>
              <a href="#"
                 class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Opensource</a>
            </li>
            <li>
              <a href="#"
                 class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <div class="max-w-7xl mx-auto">
    <slot/>
  </div>


<!--  <div id="informational-banner" tabindex="-1"-->
<!--       class="fixed bottom-0 left-0 z-50 flex flex-col justify-between w-full p-4 border-b border-gray-200 md:flex-row bg-gray-50 dark:bg-gray-700 dark:border-gray-600">-->
<!--    <div class="mb-4 md:mb-0 md:mr-4">-->
<!--      <h2 class="mb-1 text-base font-semibold text-gray-900 dark:text-white">Special Offer !!!</h2>-->
<!--      <p class="flex items-center text-sm font-normal text-gray-500 dark:text-gray-400">Take Advantage of Our Premium Web Development Services - Unleash Your Digital Potential Now!</p>-->
<!--    </div>-->
<!--    <div class="flex items-center flex-shrink-0">-->
<!--      <a href="#"-->
<!--         class="inline-flex items-center justify-center px-3 py-2 mr-3 text-xs font-medium text-gray-900 bg-white border border-gray-200 rounded-lg focus:outline-none hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">-->
<!--        <svg class="w-3 h-3 mr-2 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor"-->
<!--             viewBox="0 0 20 18">-->
<!--          <path-->
<!--              d="M9 1.334C7.06.594 1.646-.84.293.653a1.158 1.158 0 0 0-.293.77v13.973c0 .193.046.383.134.55.088.167.214.306.366.403a.932.932 0 0 0 .5.147c.176 0 .348-.05.5-.147 1.059-.32 6.265.851 7.5 1.65V1.334ZM19.707.653C18.353-.84 12.94.593 11 1.333V18c1.234-.799 6.436-1.968 7.5-1.65a.931.931 0 0 0 .5.147.931.931 0 0 0 .5-.148c.152-.096.279-.235.366-.403.088-.167.134-.357.134-.55V1.423a1.158 1.158 0 0 0-.293-.77Z"/>-->
<!--        </svg>-->
<!--        Apply Project</a>-->
<!--      <a href="#"-->
<!--         class="inline-flex items-center justify-center px-3 py-2 mr-2 text-xs font-medium text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">-->
<!--        See Portfolio-->
<!--        <svg class="w-3 h-3 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">-->
<!--          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"-->
<!--                d="M1 5h12m0 0L9 1m4 4L9 9"/>-->
<!--        </svg>-->
<!--      </a>-->
<!--      <button data-dismiss-target="#informational-banner" type="button"-->
<!--              class="flex-shrink-0 inline-flex justify-center w-7 h-7 items-center text-gray-400 hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 dark:hover:bg-gray-600 dark:hover:text-white">-->
<!--        <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">-->
<!--          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"-->
<!--                d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>-->
<!--        </svg>-->
<!--        <span class="sr-only">Close banner</span>-->
<!--      </button>-->
<!--    </div>-->
<!--  </div>-->

  <footer class="m-4 max-w-7xl mx-auto">
    <div class="w-full max-w-screen-xl mx-auto p-4 md:py-8">
      <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 Dibumi. All Rights Reserved.</span>
    </div>
  </footer>
</template>

<style scoped>

</style>