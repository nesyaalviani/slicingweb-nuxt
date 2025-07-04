<template>
  <section class="py-16 bg-gradient-to-b from-pink-400 to-purple-600 text-white text-center">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8"> <!-- padding di sini aja -->
      <h2 class="text-3xl font-bold mb-4">Student's Testimonials</h2>
      <p class="mb-12 max-w-2xl mx-auto text-purple-100">
        Here's what our students have to say about their transformative learning experience. Real stories, real growth.
      </p>

      <!-- Grid Cards -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <!-- Testimoni 1 -->
        <div class="bg-white text-gray-800 p-6 rounded-2xl shadow-lg">
          <div class="flex items-center space-x-3 mb-4">
            <img src="https://i.pinimg.com/736x/95/e8/6f/95e86fb6215dd84b90e57feb2f406b2b.jpg" class="w-10 h-10 rounded-full object-cover" />
            <div>
              <p class="font-bold text-sm">Alexa Rodriguez</p>
              <p class="text-yellow-400 text-xs">★★★★★</p>
            </div>
          </div>
          <p class="text-sm">Enrolling in courses at this elearning platform was a game-changer for me. Absolutely transformative experience!</p>
        </div>

        <!-- Testimoni 2 -->
        <div class="bg-white text-gray-800 p-6 rounded-2xl shadow-lg">
          <div class="flex items-center space-x-3 mb-4">
            <img src="https://i.pinimg.com/736x/cb/4e/64/cb4e645d958ad62a7a2aed5209d56487.jpg" class="w-10 h-10 rounded-full object-cover" />
            <div>
              <p class="font-bold text-sm">Emily Chen</p>
              <p class="text-yellow-400 text-xs">★★★★★</p>
            </div>
          </div>
          <p class="text-sm">Exceptional course! The practical insights and flexible learning structure have been instrumental in my professional growth.</p>
        </div>

        <!-- Testimoni 3 -->
        <div class="bg-white text-gray-800 p-6 rounded-2xl shadow-lg">
          <div class="flex items-center space-x-3 mb-4">
            <img src="https://i.pinimg.com/736x/7c/ba/df/7cbadf312e71bf6546a0608b78c0cf00.jpg" class="w-10 h-10 rounded-full object-cover" />
            <div>
              <p class="font-bold text-sm">James Johnson</p>
              <p class="text-yellow-400 text-xs">★★★★★</p>
            </div>
          </div>
          <p class="text-sm">Highly recommend! The personalized feedback and real-world application in the courses have elevated my understanding.</p>
        </div>
      </div>

      <!-- Pagination -->
      <div class="mt-10">
        <span class="text-white bg-white bg-opacity-20 px-4 py-1 rounded-full text-sm font-semibold">01 / 15</span>
      </div>
    </div>
  </section>
</template>
