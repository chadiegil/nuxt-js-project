<template>
  <div
    class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('https://cdn.pixabay.com/photo/2020/03/15/15/36/oldtimer-4933993_960_720.jpg')]"
  >
    <div class="z-10 absolute w-full h-full flex justify-center items-center">
      <div class="text-center w-1/2 z-20">
        <h1 class="text-8xl font-serif mb-10 text-white">Find your drive</h1>
        <!-- Home search bar -->
        <CarSearchBar />
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
  </div>
</template>
