<template>
  <section class="bg-gradient-to-br from-blue-50 to-indigo-100 section-padding relative overflow-hidden">
    <!-- Background decoration -->
    <div class="absolute inset-0 opacity-10">
      <div class="absolute top-20 left-10 w-32 h-32 bg-blue-600 rounded-full"></div>
      <div class="absolute top-40 right-20 w-24 h-24 bg-green-600 rounded-full"></div>
      <div class="absolute bottom-20 left-1/4 w-16 h-16 bg-purple-600 rounded-full"></div>
    </div>
    
    <div class="container-max relative z-10">
      <div class="max-w-4xl mx-auto text-center">
        <h1 class="text-5xl md:text-6xl font-bold text-gray-900 mb-6 leading-tight">
          Building 
          <span class="text-blue-600 relative">
            Community Governance
            <div class="absolute -bottom-2 left-0 right-0 h-1 bg-gradient-to-r from-blue-400 to-green-400 rounded-full"></div>
          </span>
        </h1>
        <p class="text-xl text-gray-600 mb-8 leading-relaxed max-w-3xl mx-auto">
          A platform for citizens to directly support public good projects, 
          without the need for government intermediaries. Building community-driven 
          governance through blockchain and the Filipino concept of Kapwa.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center mb-12">
          <button class="btn-primary text-lg px-8 py-4 shadow-lg hover:shadow-xl transform hover:-translate-y-1 transition-all duration-200">
            Start Funding Projects
          </button>
          <button class="btn-secondary text-lg px-8 py-4 shadow-lg hover:shadow-xl transform hover:-translate-y-1 transition-all duration-200">
            Learn More
          </button>
        </div>
        
        <!-- Stats or key points -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-3xl mx-auto">
          <div class="text-center">
            <div class="text-3xl font-bold text-blue-600 mb-2">100%</div>
            <div class="text-gray-600">Transparent</div>
          </div>
          <div class="text-center">
            <div class="text-3xl font-bold text-green-600 mb-2">0%</div>
            <div class="text-gray-600">Government Interference</div>
          </div>
          <div class="text-center">
            <div class="text-3xl font-bold text-purple-600 mb-2">∞</div>
            <div class="text-gray-600">Community Potential</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Component logic can be added here
</script>
