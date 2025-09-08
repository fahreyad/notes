<template>
  <div>
    <header class="bg-red-800 text-white p-4">
      <h1>Custom Layout Header</h1>
    </header>
    <main class="p-4">
      <slot />
    </main>
    <footer class="bg-red-100 text-center p-2 mt-8">
      <p>© 2025 My Nuxt App</p>
    </footer>
  </div>
</template>
