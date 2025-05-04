<!-- <template>
  <nav class="fixed top-0 left-0 w-full z-50 backdrop-blur-md bg-white/5 text-white">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="text-4xl font-light font-serif text-white">Ali Hussein</div>
      <div class="flex justify-center flex-grow">
        <ul class="flex space-x-30  text-sm font-medium">
        <li><a href="https://www.linkedin.com/in/alihusseintechandfinance/" target="_blank" class="hover:text-indigo-400 transition">LinkedIn</a></li>
        <li><a href="https://github.com/AliHusseinAs" target="_blank" class="hover:text-indigo-400 transition">GitHub</a></li>
        <li><a href="/cv.pdf" target="_blank" class="hover:text-indigo-400 transition">CV</a>
          <a href="/cv.pdf" download class="hover:text-indigo-400 transition"></a>
          </li>
      </ul>
      </div>
    </div>
  </nav>
</template> -->

<template>
  <nav class="fixed top-0 left-0 w-full z-50 backdrop-blur-md bg-white/5 text-white">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="text-4xl font-light font-serif text-white">Ali Hussein</div>
      <div class="flex justify-center flex-grow">
        <ul class="flex space-x-6 md:space-x-10 text-sm font-medium">
         
          <li><a href="https://www.linkedin.com/in/alihusseintechandfinance/" target="_blank" class="hover:text-indigo-400 transition">LinkedIn</a></li>
          <li><a href="https://github.com/AliHusseinAs" target="_blank" class="hover:text-indigo-400 transition">GitHub</a></li>
          <li>
            <a href="/cv.pdf" target="_blank" class="hover:text-indigo-400 transition">CV</a>
          </li>
          <li>
            <a
              href="mailto:alihussein10x@gmail.com"
              class="bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full shadow-md transition-colors duration-300"
            >
              Contact Me
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script setup>
// No Vue Router needed for simple in-page scrolling with href
</script>

<style scoped>
.space-x-30 > * + * { /* Corrected selector for spacing */
  margin-left: 1.875rem; /* Equivalent to space-x-30 in Tailwind (30px / 16px) */
}

@media (min-width: 768px) {
  .space-x-30 > * + * {
    margin-left: 2.5rem; /* Equivalent to md:space-x-40 (40px / 16px) - adjusted */
  }
}
</style>