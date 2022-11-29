<template>
<div class="relative flex flex-col bg-gray-200 text-gray-700 min-h-screen antialiased">
  <nav class="bg-gray-200 py-3">
    <div class="text-gray-800 flex justify-between mx-auto max-w-screen-xl pt-3 pb-4">
      <ul class="flex flex-wrap text-xl">
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
    <img src="/images/background-kunstbube.jpg" alt="kunstbube" fetchpriority="high">
    <div class="absolute top-1/2 left-1/2">
      <div class="bg-white -translate-x-1/2 -translate-y-1/2 w-80">
        <h1 class="bg-white text-8xl font-bold p-8">
          kunst<br>
          bube.
        </h1>
      </div>
    </div>
  </div>

  <div class="grid place-content-center h-48 bg-cyan-500 mb-4">
    <p class="text-white text-5xl">Der Maler mit der Kunsttube</p>
  </div>

  <div class="grid grid-cols-3 gap-4">
    <div class="overflow-hidden bg-teal-500">
      <img src="images/20211024_182054.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-teal-500">
      <img src="images/20210221_105904.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-amber-500">
      <img src="images/20210711_232308.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden bg-teal-500">
      <img src="images/20210708_233735.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-purple-500">
      <img src="images/20210710_133910.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-pink-500">
      <img src="images/20210708_233630.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden bg-yellow-500">
      <img src="images/20210210_141508.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-green-600">
      <img src="images/20210713_181816.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-emerald-500">
      <img src="images/20210714_095740.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>

    <div class="overflow-hidden bg-teal-500">
      <img src="images/20210219_192236.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-teal-500">
      <img src="images/20210710_134029.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
    <div class="overflow-hidden bg-teal-500">
      <img src="images/20210211_204515.jpg" class="h-96 object-cover w-full" alt="kunstbube">
    </div>
  </div>

  <main class="flex-grow h-96">
    <slot />
  </main>

  <footer class="bg-gray-600 justify-end text-center">
    <p class="text-white text-sm tracking-wide py-8">
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
