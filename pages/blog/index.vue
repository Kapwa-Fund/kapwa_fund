<template>
  <div class="min-h-screen bg-gray-50">
    <!-- Blog Header -->
    <section class="bg-white section-padding">
      <div class="container-max">
        <div class="max-w-4xl mx-auto text-center">
          <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">
            Kapwa Fund Blog
          </h1>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Insights on community governance, blockchain technology, and the future of decentralized public goods funding.
          </p>
        </div>
      </div>
    </section>

    <!-- Blog Posts -->
    <section class="section-padding">
      <div class="container-max">
        <div class="max-w-4xl mx-auto">
          <div class="grid gap-8">
            <!-- Featured Article -->
            <article class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition-shadow duration-300">
              <div class="p-8">
                <div class="flex items-center text-sm text-gray-500 mb-4">
                  <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-xs font-semibold mr-4">
                    Featured
                  </span>
                  <time datetime="2025-09-24">September 24, 2025</time>
                </div>
                <h2 class="text-2xl md:text-3xl font-bold text-gray-900 mb-4">
                  <NuxtLink to="/blog/introducing-kapwa-fund" class="hover:text-blue-600 transition-colors">
                    Introducing Kapwa Fund
                  </NuxtLink>
                </h2>
                <p class="text-gray-600 mb-6 leading-relaxed">
                  For centuries, governments have justified their power through the idea of a Social Contract. 
                  Today, blockchain technology allows us to imagine new ways of working together through 
                  transparent agreements enforced by code.
                </p>
                <div class="flex items-center justify-between">
                  <NuxtLink 
                    to="/blog/introducing-kapwa-fund" 
                    class="text-blue-600 font-semibold hover:text-blue-700 transition-colors"
                  >
                    Read More →
                  </NuxtLink>
                  <div class="text-sm text-gray-500">
                    8 min read
                  </div>
                </div>
              </div>
            </article>

            <!-- Coming Soon Articles -->
            <div class="grid md:grid-cols-2 gap-6">
              <article class="bg-white rounded-lg shadow-sm p-6 opacity-75">
                <div class="text-sm text-gray-500 mb-3">
                  <span class="bg-gray-100 text-gray-600 px-3 py-1 rounded-full text-xs font-semibold">
                    Coming Soon
                  </span>
                </div>
                <h3 class="text-xl font-semibold text-gray-700 mb-3">
                  The Philosophy of Kapwa
                </h3>
                <p class="text-gray-500 text-sm">
                  Exploring the Filipino concept of shared humanity and its application to decentralized governance.
                </p>
              </article>

              <article class="bg-white rounded-lg shadow-sm p-6 opacity-75">
                <div class="text-sm text-gray-500 mb-3">
                  <span class="bg-gray-100 text-gray-600 px-3 py-1 rounded-full text-xs font-semibold">
                    Coming Soon
                  </span>
                </div>
                <h3 class="text-xl font-semibold text-gray-700 mb-3">
                  Smart Contracts for Public Goods
                </h3>
                <p class="text-gray-500 text-sm">
                  How blockchain technology enables transparent and accountable funding of community projects.
                </p>
              </article>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
// SEO and meta tags
useHead({
  title: 'Blog - Kapwa Fund',
  meta: [
    { name: 'description', content: 'Insights on community governance, blockchain technology, and the future of decentralized public goods funding.' }
  ]
})
</script>
