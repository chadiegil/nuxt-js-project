<template>
  <div>
    <header
      class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md"
    >
      <a class="text-3xl font-mono" href="">Car Trader</a>
    </header>

    <!-- car detail page -->
    <div
      class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 pb-16 w-3/5"
    >
      <!-- car hero -->
      <div class="mt-10">
        <img
          src="https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
          alt="car"
          class="w-full"
        />
        <h1 class="mt-10 text-4xl">Toyota 3XLT</h1>
        <div
          class="text-slate-500 flex text-lg mt-3 border-b pb-5 justify-between"
        >
          <div class="flex">
            <p class="mr-2">6 seats</p>
            <p class="mr-2">-</p>
            <p class="mr-2">5023,4242 miles</p>
          </div>
          <div class="font-bold text-2xl">$234,4242</div>
        </div>
      </div>
      <!-- car attributes -->
      <div class="mr-10 mt-5 border-b pb-5">
        <div class="flex text-lg mt-2">
          <p class="rounded text-line-800 mr-3">✔</p>
          <p>Leather Interior</p>
        </div>
      </div>
      <!-- car description -->
      <div class="mt-5">
        <p class="mb-10">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis,
          explicabo. Odio, quisquam assumenda tenetur est velit ratione
          reiciendis autem quos.
        </p>
      </div>
      <!-- car contact -->
      <div class="mt-10">
        <div class="flex w-600 justify-between">
          <input type="text" class="border p-1" placeholder="name" />
          <input type="text" class="border p-1" placeholder="email" />
          <input type="text" class="border p-1" placeholder="phone" />
        </div>

        <div class="flex mt-4 w-full">
          <textarea class="border p-1 w-full" placeholder="Message"></textarea>
        </div>
        <button class="bg-blue-400 text-white px-10 py-3 rounded mt-4">
          Submit
        </button>
      </div>
    </div>
  </div>
</template>
