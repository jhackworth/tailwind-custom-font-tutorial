<template>
  <div class="container mx-auto mt-12 px-5">
    <div class="text-center bg-red-200 py-2 mx-2 my-3 rounded xl:hidden">
      <p>
        This page wasn't setup to be responsive and probably looks weird at this resolution — sorry!
      </p>
    </div>

    <div class="flex flex-wrap justify-start">
      <div class="h-56 w-40 bg-yellow-500"></div>

      <div class="pt-8 -ml-32">
        <h1 class="text-6xl font-dm-serif">A Luxurious Headline</h1>
        <p class="text-sm font-inter uppercase tracking-wide ml-32 pl-2 italic -mt-2">Supporting text goes here</p>
      </div>
    </div>

    <div class="flex flex-row items-start mb-24">
      <div class="mt-10 pl-4 pr-16 w-3/5">
        <h1 class="font-dm-serif text-3xl">Subheadline here</h1>
        <p class="font-inter">
          Curabitur dictum metus et orci tristique pharetra. Sed non eleifend lacus. In fringilla nunc quis gravida iaculis. Duis facilisis sollicitudin turpis ac dignissim. Nulla gravida libero vel eros iaculis ultrices. Aenean eros justo, gravida sed libero id, ornare placerat eros. Nullam condimentum metus ut quam tincidunt, sit amet mattis nisi dapibus. Sed leo diam, commodo eu magna eu, facilisis tempor velit. Sed imperdiet lectus libero, dapibus blandit velit sollicitudin sit amet.
        </p>
        <p class="font-inter mt-5">  
          Vestibulum sit amet dictum lorem. Pellentesque vehicula convallis sapien ut interdum. Nullam est ipsum, euismod vel tortor ac, gravida placerat est. Nullam auctor nec nibh accumsan mattis. Aenean purus quam, interdum sit amet orci sit amet, cursus tincidunt ex. Nam consectetur tortor nec auctor maximus. Nullam euismod lorem rhoncus justo consequat blandit. Sed sagittis bibendum dolor sollicitudin volutpat. Duis semper vulputate mauris sit amet eleifend. Donec euismod purus non lacus fringilla molestie.
        </p>
        <p class="font-inter mt-5">  
          Praesent id metus gravida, cursus justo a, sodales nulla. In venenatis tincidunt lorem, a vestibulum enim mollis a. Nullam sit amet fermentum ex. Ut imperdiet, arcu ut placerat pulvinar, est nisl imperdiet tortor, eget bibendum tellus dolor in ipsum. Nunc turpis urna, auctor sed ullamcorper sit amet, pretium et quam. Donec elementum nulla eget tempus aliquam. Suspendisse mollis enim justo, vel sagittis massa euismod eu. Pellentesque porta maximus justo, vitae semper ante ultrices non. Phasellus pulvinar ligula in est pellentesque, nec ullamcorper quam porta. Integer nec turpis ac magna finibus placerat. Ut at tempus orci.
        </p>
      </div>

      <div class="w-2/5">
        <img src="./assets/img/fashion.jpg" class="img -mt-5">
        <p class="text-xs font-inter font-medium italic text-right">Photo by <a class="underline" href="https://unsplash.com/@ohthehumanity" target="_blank">Dom Hill</a> on <a class="underline" href="https://unsplash.com" target="_blank">Unsplash</a></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    
  }
}
</script>

<style>
.img {
  box-shadow: 7px 7px 0px 0px #ecc94b;
}
</style>
