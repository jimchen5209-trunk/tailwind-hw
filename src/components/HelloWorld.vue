<template>
  <div class="container mx-auto px-4 flex flex-col items-center">
    <div class="w-32 h-32 p-8 m-2 border border-purple-500 rounded-xl bg-blue-200"></div>
    <p class="text-blue-900 bg-[#ccc] w-32">我是文字</p>
    <div>
      <button
        class="m-2 px-8 py-2 rounded-[50px] bg-blue-300 text-gray-800 hover:bg-blue-800 hover:text-gray-300">按鈕</button>
      <button
        class="m-2 px-8 py-2 rounded-[50px] bg-blue-300 text-gray-800 hover:bg-blue-800 hover:text-gray-300 focus:outline-xl focus:outline-red-800">焦點按鈕</button>
    </div>
    <div>
      <button
        class="m-2 px-8 py-2 rounded-[50px] bg-blue-400 sm:bg-green-400 md:bg-yellow-500 lg:bg-red-500">斷點按鈕</button>
    </div>
  </div>
</template>
