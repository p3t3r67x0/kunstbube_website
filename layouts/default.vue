<template>
<div class="relative flex flex-col bg-gray-200 text-gray-700 min-h-screen antialiased">
  <nav class="bg-gray-200 p-2 sm:px-0 sm:py-3">
    <div class="text-gray-800 flex justify-between mx-auto max-w-screen-xl md:pt-3 md:pb-4">
      <ul class="flex flex-wrap sm:text-xl">
        <li class="mr-6">
          <a href="#">Start</a>
        </li>
        <li class="mr-6">
          <a href="#">About</a>
        </li>
        <li class="mr-6">
          <a href="#">Gallerie</a>
        </li>
        <li class="mr-6">
          <a href="#">Nichts</a>
        </li>
      </ul>
    </div>
  </nav>

  <div class="relative">
    <img src="/images/background-kunstbube.jpg" class="min-h-96 object-cover w-full" alt="kunstbube" fetchpriority="high">
    <div class="absolute top-1/2 left-1/2">
      <div class="bg-white -translate-x-1/2 -translate-y-1/2 w-48 sm:w-72 md:w-80">
        <h1 class="bg-white text-3xl sm:text-6xl md:text-8xl font-bold p-4 sm:p-6 md:p-8">
          kunst<br>
          bube.
        </h1>
      </div>
    </div>
  </div>

  <div class="grid place-content-center h-48 bg-cyan-500 mb-4">
    <p class="text-white text-5xl">Der Maler mit der Kunsttube</p>
  </div>

  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 xl:grid-cols-4 gap-2 sm:gap-3 md:gap-4 px-2 sm:px-0">
    <div class="overflow-hidden">
      <img src="/images/20211024_182054.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210221_105904.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210711_232308.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden">
      <img src="/images/20210708_233735.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210710_133910.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210708_233630.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden">
      <img src="/images/20210210_141508.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210713_181816.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210714_095740.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden">
      <img src="/images/20210219_192236.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210710_134029.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden">
      <img src="/images/20210211_204515.jpg" class="h-48 sm:h-72 md:h-96 object-cover w-full" alt="kunstbube">
    </div>
  </div>

  <main class="flex-grow h-96 px-2 sm:px-0">
    <slot />
  </main>

  <footer class="bg-gray-600 justify-end text-center">
    <p class="text-white text-sm tracking-wide py-3 sm:py-6 md:py-8">
      powered with
      <span class="text-red-500" role="img" aria-label="Love">
        ♥
      </span>
      by <a href="https://kunstbube.com">kunstbube.</a>
    </p>
  </footer>
</div>
</template>

<script>
export default {}
</script>

<style lang="css" scoped>
</style>
