<template>
  <div id="app" class="flex bg-gray-100 font-body">
    <div class="w-2/6 bg-white min-h-screen shadow-md relative select-none">
      <div
        class="block absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2"
      >
        <span class="block text-center text-green-500 font-black text-8xl"
          >DLX</span
        >
        <span class="block text-center text-black font-bold text-xl"
          >e x a m i n e</span
        >
        <p class="my-10 text-center">
          Deep learning x-ray for use in Airports and other luggage x-ray
          applications.
        </p>
      </div>
    </div>
    <div class="w-4/6 min-h-screen relative">
      <div
        class="bg-white self-center px-40 py-8 mx-auto w-1/2 shadow-md absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2 rounded-md"
      >
        <h1 class="text-black font-700 text-3xl text-center mb-8">
          Account Login
        </h1>
        <input
          class="flex mb-4 mx-auto shadow-sm px-4 py-3 leading-5 border rounded-md focus:outline-none focus:ring focus:ring-green-500 focus:border-green-500"
          type="text"
          placeholder="User ID"
        />
        <input
          class="flex mx-auto shadow-sm px-4 py-3 leading-5 border rounded-md focus:outline-none focus:ring focus:ring-green-500 focus:border-green-500"
          type="password"
          placeholder="Password"
          id=""
        />
        <button
          class="flex mx-auto border-2 shadow-sm px-4 py-3 mt-24 rounded-md font-bold transition duration-500 ease-in-out border-green-500 hover:bg-green-500 transform hover:-translate-y-1 hover:scale-110"
        >
          Login
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
</style>