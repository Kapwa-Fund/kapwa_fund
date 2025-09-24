<template>
  <div class="min-h-screen bg-white">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
      <nav class="container-max">
        <div class="flex justify-between items-center py-4 px-4 sm:px-6 lg:px-8">
          <div class="flex items-center">
            <NuxtLink to="/" class="text-2xl font-bold text-blue-600">
              Kapwa Fund
            </NuxtLink>
          </div>
          <div class="hidden md:flex space-x-8">
            <a href="#problem" class="text-gray-700 hover:text-blue-600 transition-colors">The Problem</a>
            <a href="#solution" class="text-gray-700 hover:text-blue-600 transition-colors">Kapwa Solution</a>
            <a href="#how-it-works" class="text-gray-700 hover:text-blue-600 transition-colors">How It Works</a>
            <a href="#vision" class="text-gray-700 hover:text-blue-600 transition-colors">Vision</a>
            <NuxtLink to="/blog" class="text-gray-700 hover:text-blue-600 transition-colors">Blog</NuxtLink>
          </div>
          <div class="flex items-center space-x-4">
            <button class="btn-primary">
              Get Started
            </button>
            <button
              class="md:hidden"
              aria-label="Toggle navigation menu"
              :aria-expanded="isMobileMenuOpen ? 'true' : 'false'"
              @click="isMobileMenuOpen = !isMobileMenuOpen"
            >
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
              </svg>
            </button>
          </div>
        </div>
        <!-- Mobile menu -->
        <div
          class="md:hidden"
          v-show="isMobileMenuOpen"
        >
          <div class="px-4 pb-4 space-y-2">
            <a href="#problem" class="block px-3 py-2 rounded-lg text-gray-700 hover:bg-gray-100">The Problem</a>
            <a href="#solution" class="block px-3 py-2 rounded-lg text-gray-700 hover:bg-gray-100">Kapwa Solution</a>
            <a href="#how-it-works" class="block px-3 py-2 rounded-lg text-gray-700 hover:bg-gray-100">How It Works</a>
            <a href="#vision" class="block px-3 py-2 rounded-lg text-gray-700 hover:bg-gray-100">Vision</a>
            <NuxtLink to="/blog" class="block px-3 py-2 rounded-lg text-gray-700 hover:bg-gray-100">Blog</NuxtLink>
          </div>
        </div>
      </nav>
    </header>

    <!-- Main Content -->
    <main>
      <slot />
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white">
      <div class="container-max section-padding px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
          <div class="col-span-1 md:col-span-2">
            <h3 class="text-2xl font-bold mb-4">Kapwa Fund</h3>
            <p class="text-gray-300 mb-4">
              Building community-driven governance through blockchain and the Filipino concept of Kapwa.
            </p>
            <p class="text-gray-400 text-sm">
              Building community governance, one project at a time.
            </p>
          </div>
          <div>
            <h4 class="font-semibold mb-4">Platform</h4>
            <ul class="space-y-2 text-gray-300">
              <li><a href="#how-it-works" class="hover:text-white transition-colors">How It Works</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Submit Project</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Browse Projects</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Become Auditor</a></li>
            </ul>
          </div>
          <div>
            <h4 class="font-semibold mb-4">Resources</h4>
            <ul class="space-y-2 text-gray-300">
              <li><a href="#" class="hover:text-white transition-colors">Documentation</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Whitepaper</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Community</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Contact</a></li>
            </ul>
          </div>
        </div>
        <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
          <p>&copy; 2025 Kapwa Fund. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
import { ref, onMounted, onUnmounted } from 'vue'

const isMobileMenuOpen = ref(false)

// Close menu on route change
const router = useRouter()
router.afterEach(() => {
  isMobileMenuOpen.value = false
})

// Close on escape key
const onKeydown = (e: KeyboardEvent) => {
  if (e.key === 'Escape') {
    isMobileMenuOpen.value = false
  }
}

onMounted(() => {
  window.addEventListener('keydown', onKeydown)
})

onUnmounted(() => {
  window.removeEventListener('keydown', onKeydown)
})
</script>
