<template>
  <div>
    <header class="bg-gray-800 text-white p-4">
      <Header />
    </header>
    <main class="p-4">
      <slot />
    </main>
    <footer class="bg-gray-100 text-center p-2 mt-8">
      <p>© 2025 My Nuxt App</p>
    </footer>
  </div>
</template>
