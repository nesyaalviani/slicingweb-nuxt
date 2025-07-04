<template>
    <section class="grid md:grid-cols-2 gap-10 px-4 sm:px-6 lg:px-8 pb-20 items-center max-w-7xl mx-auto">
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
        <div class="space-y-5 px-4">
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
</template>