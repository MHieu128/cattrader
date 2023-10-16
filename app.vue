<template>
  <div>
    <header class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md">
      <a class="text-3xl font-mono" href="">Cat Trader</a>
    </header>
    <div class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url(https://media.post.rvohealth.io/wp-content/uploads/2020/07/petting_pet_cat-1200x628-facebook-1200x628.jpg)]">
        <div class="z-10 absolute w-full h-full flex justify-center items-center">
          <div class="text-center w-1/2">
            <h1 class="text-8xl font-serif mb-10 text-white">Find your cat</h1>
            <div class="font-serif w-[100%] text-2xl rounded-full bg-white flex justify-between overflow-hidden drop-shadow-2xl mx-auto">
              <input type="text" class="py-3 px-5 w-full text-2xl rounded-full focus:outline-none" placeholder="Search by cat type...">
              <button class="bg-cyan-500 px-10 text-white">Search</button>
            </div>
          </div>
        </div>
        <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
    <div class="bg-neutral-200 p-6 text-center white:bg-neutral-5300">
      <span>© 2023 Copyright:</span>
      <a
        class="font-semibold text-neutral-600 dark:text-neutral-400">HieuLM13</a
      >
  </div>
  </div>
</template>
