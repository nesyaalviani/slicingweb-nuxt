<template>
    <section class="bg-gradient-to-br from-[#f4e7ff] to-[#fcd7f8] py-20 px-4 sm:px-6 lg:px-8 flex flex-col-reverse md:flex-row items-center justify-between gap-12 relative overflow-hidden max-w-7xl mx-auto">
        <!-- Text Content -->
        <div class="md:w-1/2 space-y-6 z-10 px-4">
          <h2 class="text-4xl font-extrabold text-gray-900 leading-snug">
            If You Are A Certified Teacher <br />
            <span class="text-purple-600">Then Become An Instructor</span>
          </h2>
          <p class="text-gray-600 text-base max-w-lg">
            Unlock the opportunity to inspire and educate by joining our team of instructors. If you're a certified teacher, elevate your impact and share your expertise with learners worldwide.
          </p>

          <!-- Keuntungan List -->
          <div class="grid grid-cols-2 gap-3 text-sm text-gray-700">
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Global Impact</span></div>
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Creative Freedom</span></div>
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Flexible Schedule</span></div>
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Professional Development</span></div>
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Innovative Tools</span></div>
            <div class="flex items-center space-x-2"><span class="text-purple-600">✔️</span><span>Networking Opportunities</span></div>
          </div>

          <button class="mt-6 px-6 py-3 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-semibold hover:opacity-90 transition">
            Become an Instructor
          </button>
        </div>

        <!-- Image Side -->
        <div class="md:w-1/2 flex justify-center relative z-10 px-4">
          <div class="relative">
            <!-- Decorative Dotted Circle -->
            <div class="absolute -top-6 -right-6 w-[320px] h-[320px] border-4 border-dotted border-pink-300 rounded-full z-0"></div>
            <!-- Gambar -->
            <img src="https://i.pinimg.com/736x/e2/96/4b/e2964bfa57bdc50a36c60bda294941b6.jpg" alt="Instructor" class="relative z-10 w-[300px] h-[300px] object-cover rounded-full shadow-xl border-8 border-white" />
          </div>
        </div>
    </section>
</template>