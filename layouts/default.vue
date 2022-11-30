<template>
<div class="relative flex flex-col text-gray-700 min-h-screen antialiased">
  <div class="relative">
    <nav class="absolute top-0 inset-x-0 z-50 bg-gray-800 p-3 sm:px-0">
      <div class="text-white flex justify-between mx-auto max-w-screen-xl md:pt-3 md:pb-4">
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

    <img src="/images/background-kunstbube.jpg" class="h-screen z-0 object-cover w-full" alt="kunstbube" fetchpriority="high">

    <div class="absolute top-1/2 left-1/2">
      <div class="bg-white -translate-x-1/2 -translate-y-1/2 w-28 sm:w-48 md:w-80">
        <h1 class="bg-white text-3xl sm:text-6xl md:text-8xl font-bold p-4 sm:p-6 md:p-8">
          kunst<br>
          bube.
        </h1>
      </div>
    </div>
  </div>

  <div class="md:min-h-48 bg-gray-800 p-3 md:py-6">
    <div class="container mx-auto max-w-screen-xl">
      <h2 class="text-gray-500 md:text-5xl mb-3">Was kann kunstbube.</h2>
      <p class="text-gray-200 md:text-2xl">Moderne Kunst sollte für alle zugänglich und offen sein. Aus diesem Grund teile ich meine Werke in Online Gallerien zum vervielfältigen für jeden, für immer und kostenlos. Die
        Originale stehen dem Sammler und Abenteurer zur Verfügung. Mein Malstil ist eher impulsiv und spontan. Ich betrachte eine weiße Leinwand wie eine Bühne, stelle mir eine Farbpalette zusammen und lade den Pinsel mit den Farben ein das
        Theaterstück aufzuführen. Ich spiele mit der Leuchtkraft der Farben auf der Fläche und der Leichtigkeit des Wassers. Es entstehen so ungeahnte Texturen und Formen in vielen Schichten. In dieser Theateraufführung entsteht eine Tiefe von
        ausdrucksstarken Protagonisten. Vielleicht werden Sie in dem ein oder anderen Werk Ihre eigene Uraufführung sehen.</p>
    </div>
  </div>

  <div class="bg-gray-600 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-2 sm:gap-3 md:gap-4 px-2 sm:px-0 p-2 md:py-4">
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

  <main class="flex-grow bg-gray-800 h-96 p-2 text-white">
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
