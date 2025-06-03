<script setup></script>
<template>
  <div>
    <header style="background: #222; color: #fff; padding: 1rem;">
      <h1>Mi Tienda de Corbatas</h1>
      <nav>
        <NuxtLink to="/">Inicio</NuxtLink> |
        <NuxtLink to="/modahombre">Moda Hombre</NuxtLink> |
        <NuxtLink to="/modamujer">Moda Mujer</NuxtLink> |
        <NuxtLink to="/corbatashombre">Corbatas Hombre</NuxtLink>
      </nav>
    </header>
    <main>
      <NuxtPage />
    </main>
    <footer style="background: #222; color: #fff; padding: 1rem; margin-top: 2rem;">
      <p>&copy; 2025 Mi Tienda de Corbatas</p>
    </footer>
  </div>
</template>
