<template>
  <div>
    <Navbar />
    
    <!-- Hero Section -->
      <section class="flex flex-col-reverse md:flex-row items-center justify-between px-8 py-16 bg-[#fdfcff] relative">
        <!-- Left Text -->
        <div class="md:w-1/2 space-y-6">
          <h2 class="text-4xl sm:text-5xl font-extrabold text-gray-900 leading-tight">
            Kembangkan keterampilan Anda <br />
            dengan cara yang baru <br />
            dan unik
          </h2>
          <p class="text-gray-600 max-w-md">
            Jelajahi pendekatan transformatif untuk pengembangan keterampilan di platform pembelajaran daring kami. Temukan ranah baru pengalaman belajar dan tingkatkan keahlian Anda dengan cara yang unik.
          </p>
          <div class="flex items-center space-x-6">
            <button class="px-6 py-3 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-lg font-semibold hover:opacity-90">Daftar Sekarang</button>
            <a href="#" class="flex items-center text-purple-600 font-medium text-sm">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
              Apa itu Etech?
            </a>
          </div>
        </div>

        <!-- Right Image -->
        <div class="md:w-1/2 relative mt-10 md:mt-0">
          <!-- Circle background effect -->
          <div class="absolute z-0 top-0 right-0 w-[260px] h-[260px] rounded-full bg-purple-100 md:block hidden"></div>

          <!-- Image -->
          <img src="https://i.pinimg.com/736x/0d/08/d8/0d08d85c0baa936ee69e66ef43df4784.jpg" alt="Student" class="relative z-10 rounded-xl w-full max-w-sm mx-auto" />

          <!-- 50+ Online Courses -->
          <div class="absolute top-6 left-6 bg-white px-4 py-2 rounded-xl shadow-md text-xs font-semibold text-gray-700 flex items-center space-x-2 z-20">
            <div class="bg-purple-100 text-purple-600 p-1 rounded-full text-xs">←</div>
            <span><span class="text-purple-600">50+</span> Online Courses</span>
          </div>

          <!-- 10k+ Online Students -->
          <div class="absolute top-1/3 right-2 bg-white px-4 py-2 rounded-xl shadow-md text-xs font-semibold text-gray-700 z-20">
            <span class="text-purple-600">10k+</span> Online Students
            <div class="flex space-x-1 mt-2">
              <img src="https://placehold.co/20x20" class="rounded-full" />
              <img src="https://placehold.co/20x20" class="rounded-full" />
              <img src="https://placehold.co/20x20" class="rounded-full" />
              <img src="https://placehold.co/20x20" class="rounded-full" />
            </div>
          </div>

          <!-- UI Design Class -->
          <div class="absolute bottom-8 left-1/2 -translate-x-1/2 bg-white px-4 py-3 rounded-xl shadow text-sm w-[210px] z-20">
            <div class="flex items-center space-x-2">
              <img src="https://placehold.co/24x24" class="rounded-full" />
              <div>
                <p class="text-gray-700 font-semibold">UI Design Class</p>
                <p class="text-xs text-gray-400">Today at 02:00 PM</p>
              </div>
            </div>
            <button class="mt-2 text-xs px-3 py-1 bg-gradient-to-r from-purple-500 to-pink-500 text-white rounded-md font-semibold w-full">Join now</button>
          </div>
        </div>
      </section>

      <!-- Partner Logos -->
      <section class="bg-gradient-to-r from-purple-500 to-pink-500 py-6">
        <div class="flex justify-center items-center gap-10 flex-wrap px-4">
          <img src="img/duolingo.svg" alt="Duolingo" class="h-6 object-contain" />
          <img src="img/codecov.svg" alt="Codecov" class="h-6 object-contain" />
          <img src="img/usertesting.svg" alt="UserTesting" class="h-6 object-contain" />
        </div>
      </section>

      <!-- Search Courses -->
      <section class="py-14 text-center px-4">
        <h3 class="text-2xl font-extrabold text-gray-800 mb-6">Cari Kursus</h3>
        <div class="flex justify-center">
          <div class="flex bg-white rounded-full shadow-md overflow-hidden">
            <div class="flex items-center px-4 text-purple-600">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-4.35-4.35m0 0A7.5 7.5 0 103 10.5a7.5 7.5 0 0013.15 6.15z" />
              </svg>
            </div>
            <input type="text" placeholder="Cari dari 50+ kursus"
              class="px-4 py-2 w-72 focus:outline-none rounded-l-full" />
            <button
              class="px-6 py-2 bg-gradient-to-r from-purple-500 to-pink-500 text-white font-medium rounded-r-full hover:from-purple-600 hover:to-pink-600 transition">
              Cari
            </button>
          </div>
        </div>
      </section>

    <!-- Benefits Section -->
    <section class="grid md:grid-cols-2 gap-10 px-10 pb-20 items-center">
      <!-- Gambar grid -->
      <div class="flex justify-center">
        <div class="border-2 border-dashed border-pink-400 rounded-[36px] p-[6px]">
          <div class="grid grid-cols-2 grid-rows-2 gap-[4px] rounded-[30px] overflow-hidden"
              style="width: 280px; height: 280px;">
            <img src="/img/gambar 2.jpg" alt="" class="object-cover w-full h-full" />
            <img src="/img/gambar 5.jpg" alt="" class="object-cover w-full h-full" />
            <img src="/img/gambar 6.jpg" alt="" class="object-cover w-full h-full" />
            <img src="/img/gambar 3.jpg" alt="" class="object-cover w-full h-full" />
          </div>
        </div>
      </div>

        <!-- Benefit list -->
        <div class="space-y-5">
          <h3 class="text-xl sm:text-2xl font-semibold text-gray-800">
            <span class="text-pink-500 font-bold">Manfaat</span> dari Pembelajaran Online Kami
          </h3>
          <ul class="space-y-4 text-gray-700 text-sm sm:text-base">
            <li class="flex items-start gap-3">
              <span class="text-purple-600 text-xl">🎓</span>
              <p><strong>Gelar Online:</strong> Dapatkan gelar resmi langsung dari rumahmu, membuka peluang karier lebih luas.</p>
            </li>
            <li class="flex items-start gap-3">
              <span class="text-pink-500 text-xl">⏱</span>
              <p><strong>Kursus Pendek:</strong> Belajar cepat dengan materi singkat dan langsung ke intinya.</p>
            </li>
            <li class="flex items-start gap-3">
              <span class="text-purple-600 text-xl">👨‍🏫</span>
              <p><strong>Pelatihan dari Ahli:</strong> Dipandu langsung oleh para mentor profesional dan berpengalaman.</p>
            </li>
            <li class="flex items-start gap-3">
              <span class="text-pink-500 text-xl">🎥</span>
              <p><strong>1.5k+ Video Kursus:</strong> Akses perpustakaan video interaktif dari berbagai topik favoritmu.</p>
            </li>
          </ul>
        </div>
      </section>

      <!-- Section: Kursus Terpopuler -->
      <section class="py-16 bg-gradient-to-r from-purple-500 to-pink-400 text-white text-center">
        <h2 class="text-3xl font-extrabold mb-4">Kursus Terpopuler Kami</h2>
        <p class="text-white/90 max-w-2xl mx-auto mb-12 text-sm sm:text-base">
          Temukan kursus yang paling diminati, disusun dengan hati untuk memenuhi kebutuhan pembelajaran masa kini. Jelajahi konten menarik demi kesuksesan di setiap langkah perjalanan edukasimu.
        </p>

        <div class="grid md:grid-cols-3 gap-8 px-8 max-w-7xl mx-auto">
          <!-- Card -->
         <div class="bg-white text-gray-800 rounded-xl shadow-md w-[280px] sm:w-[300px] mx-auto">
            <div class="w-full h-[130px] overflow-hidden rounded-t-xl">
              <img src="img/gambar 7.jpeg" alt="Web Design" class="w-full h-full object-cover object-center" />
            </div>
            <div class="p-5 text-left">
              <div class="flex justify-between items-center mb-2">
                <span class="bg-purple-100 text-purple-600 text-xs px-3 py-1 rounded-full">Desain Web</span>
                <span class="text-sm text-yellow-500 font-semibold">⭐ 4.9</span>
              </div>
              <h3 class="text-lg font-bold">Desain & Pengembangan Web</h3>
              <p class="text-sm text-gray-500 mt-1">25 Kelas · 185 Siswa</p>
              <p class="font-semibold mt-2">$560.00</p>
              <div class="flex items-center mt-3 space-x-2">
                <img src="https://i.pinimg.com/736x/0f/81/f0/0f81f0a8a1ec5ff443696c10fff7a543.jpg" class="w-10 h-10 rounded-full object-cover" />
                <span class="text-sm text-gray-700">J. Morgan</span>
              </div>
            </div>
          </div>

          <!-- Card -->
         <div class="bg-white text-gray-800 rounded-xl shadow-md w-[280px] sm:w-[300px] mx-auto">
           <div class="w-full h-[130px] overflow-hidden rounded-t-xl">
              <img src="img/gambar 8.jpeg" alt="UI/UX Design" class="w-full h-full object-cover object-center" />
            </div>
            <div class="p-5 text-left">
              <div class="flex justify-between items-center mb-2">
                <span class="bg-purple-100 text-purple-600 text-xs px-3 py-1 rounded-full">UI/UX Design</span>
                <span class="text-sm text-yellow-500 font-semibold">⭐ 5.0</span>
              </div>
              <h3 class="text-lg font-bold">Wireframing & Prototyping</h3>
              <p class="text-sm text-gray-500 mt-1">8 Kelas · 400 Siswa</p>
              <p class="font-semibold mt-2">$160.00</p>
              <div class="flex items-center mt-3 space-x-2">
                <img src="https://i.pinimg.com/736x/0a/f5/27/0af527a83574bd1395a403afa7deaf4c.jpg" class="w-10 h-10 rounded-full object-cover" />
                <span class="text-sm text-gray-700">Jordan Re</span>
              </div>
            </div>
          </div>

          <!-- Card -->
          <div class="bg-white text-gray-800 rounded-xl shadow-md w-[280px] sm:w-[300px] mx-auto">
            <div class="w-full h-[130px] overflow-hidden rounded-t-xl">
              <img src="img/gambar 9.jpeg" alt="Data Science" class="w-full h-full object-cover object-center" />
            </div>
            <div class="p-5 text-left">
              <div class="flex justify-between items-center mb-2">
                <span class="bg-purple-100 text-purple-600 text-xs px-3 py-1 rounded-full">Data Science</span>
                <span class="text-sm text-yellow-500 font-semibold">⭐ 4.9</span>
              </div>
              <h3 class="text-lg font-bold">Python untuk Data Science</h3>
              <p class="text-sm text-gray-500 mt-1">18 Kelas · 160 Siswa</p>
              <p class="font-semibold mt-2">$432.00</p>
              <div class="flex items-center mt-3 space-x-2">
                <img src="https://i.pinimg.com/736x/31/7d/53/317d5395b5353b54c728a9040507ff01.jpg" class="w-10 h-10 rounded-full object-cover" />
                <span class="text-sm text-gray-700">Alex Taylor</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Section: Menjadi Pengajar -->
      <section class="bg-gradient-to-br from-[#f4e7ff] to-[#fcd7f8] py-20 px-8 flex flex-col-reverse md:flex-row items-center justify-between gap-12 relative overflow-hidden">
        <!-- Text Content -->
        <div class="md:w-1/2 space-y-6 z-10">
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
        <div class="md:w-1/2 flex justify-center relative z-10">
          <div class="relative">
            <!-- Decorative Dotted Circle -->
            <div class="absolute -top-6 -right-6 w-[320px] h-[320px] border-4 border-dotted border-pink-300 rounded-full z-0"></div>
            <!-- Gambar -->
            <img src="https://i.pinimg.com/736x/e2/96/4b/e2964bfa57bdc50a36c60bda294941b6.jpg" alt="Instructor" class="relative z-10 w-[300px] h-[300px] object-cover rounded-full shadow-xl border-8 border-white" />
          </div>
        </div>
      </section>

      <!-- Section: Testimonials -->
      <section class="py-16 px-8 bg-gradient-to-b from-pink-400 to-purple-600 text-white text-center">
        <h2 class="text-3xl font-bold mb-4">Student’s Testimonials</h2>
        <p class="mb-12 max-w-2xl mx-auto text-purple-100">
          Here's what our students have to say about their transformative learning experience. Real stories, real growth.
        </p>

        <div class="grid md:grid-cols-3 gap-8">
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

        <!-- Pagination (simbol aja) -->
        <div class="mt-10">
          <span class="text-white bg-white bg-opacity-20 px-4 py-1 rounded-full text-sm font-semibold">01 / 15</span>
        </div>
      </section>

      <!-- Section: Get In Touch -->
      <section class="bg-white py-16 px-8 text-center">
        <div class="max-w-lg mx-auto bg-gradient-to-r from-purple-500 to-pink-500 text-white p-8 rounded-2xl shadow-lg">
          <h2 class="text-2xl font-bold mb-2">Get In Touch!</h2>
          <p class="mb-6 text-sm">Subscribe to get in touch and to enjoy discounts, promos and much more!</p>
          <div class="flex flex-col sm:flex-row justify-center gap-3">
            <input type="email" placeholder="Enter your email..." class="px-4 py-2 w-full sm:w-auto rounded-lg text-gray-800 focus:outline-none" />
            <button class="px-6 py-2 bg-white text-purple-600 rounded-lg font-semibold hover:bg-gray-100 transition">Subscribe</button>
          </div>
        </div>
      </section>
    <Footer />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>
