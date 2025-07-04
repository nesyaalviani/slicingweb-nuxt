<template>
  <section
    class="flex flex-col-reverse md:flex-row items-center justify-between px-4 sm:px-6 lg:px-8 py-16 bg-[#fdfcff] relative max-w-7xl mx-auto"
  >
    <!-- Left Text -->
    <div class="md:w-1/2 space-y-6 px-4">
      <h2
        class="text-4xl sm:text-5xl font-extrabold text-gray-900 leading-tight"
      >
        Kembangkan keterampilan Anda <br />
        dengan cara yang baru <br />
        dan unik
      </h2>
      <p class="text-gray-600 max-w-md">
        Jelajahi pendekatan transformatif untuk pengembangan keterampilan di
        platform pembelajaran daring kami. Temukan ranah baru pengalaman belajar
        dan tingkatkan keahlian Anda dengan cara yang unik.
      </p>
      <div class="flex items-center space-x-6">
        <button
          class="px-6 py-3 transition-transform hover:scale-105 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-semibold hover:opacity-90"
        >
          Daftar Sekarang
        </button>
        <a
          href="#"
          class="flex items-center text-purple-600 font-medium text-sm"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4 mr-1"
            fill="currentColor"
            viewBox="0 0 24 24"
          >
            <path d="M8 5v14l11-7z" />
          </svg>
          Apa itu Etech?
        </a>
      </div>
    </div>

    <!-- Right Image -->
    <div class="md:w-1/2 relative mt-10 md:mt-0 px-4">
      <!-- Circle background effect -->
      <div
        class="absolute z-0 top-0 right-0 w-[260px] h-[260px] rounded-full bg-purple-100 md:block hidden"
      ></div>

      <!-- Image -->
      <img
        src="https://i.pinimg.com/736x/0d/08/d8/0d08d85c0baa936ee69e66ef43df4784.jpg"
        alt="Student"
        class="relative z-10 rounded-xl w-full max-w-sm mx-auto"
      />

      <!-- 50+ Online Courses -->
      <div
        class="absolute top-6 left-6 bg-white px-4 py-2 rounded-xl shadow-md text-xs font-semibold text-gray-700 flex items-center space-x-2 z-20"
      >
        <div class="bg-purple-100 text-purple-600 p-1 rounded-full text-xs">
          ←
        </div>
        <span><span class="text-purple-600">50+</span> Online Courses</span>
      </div>

      <!-- 10k+ Online Students -->
      <div
        class="absolute top-1/3 right-2 bg-white px-4 py-2 rounded-xl shadow-md text-xs font-semibold text-gray-700 z-20"
      >
        <span class="text-purple-600">10k+</span> Online Students
        <div class="flex space-x-1 mt-2">
          <img src="https://placehold.co/20x20" class="rounded-full" />
          <img src="https://placehold.co/20x20" class="rounded-full" />
          <img src="https://placehold.co/20x20" class="rounded-full" />
          <img src="https://placehold.co/20x20" class="rounded-full" />
        </div>
      </div>

      <!-- UI Design Class -->
      <div
        class="absolute bottom-8 left-1/2 -translate-x-1/2 bg-white px-4 py-3 rounded-xl shadow text-sm w-[210px] z-20"
      >
        <div class="flex items-center space-x-2">
          <img src="https://placehold.co/24x24" class="rounded-full" />
          <div>
            <p class="text-gray-700 font-semibold">UI Design Class</p>
            <p class="text-xs text-gray-400">Today at 02:00 PM</p>
          </div>
        </div>
        <button
          class="mt-2 text-xs px-3 py-1 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-md font-semibold w-full"
        >
          Join now
        </button>
      </div>
    </div>
  </section>
</template>
