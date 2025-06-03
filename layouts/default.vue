<script setup></script>
<template>
  <div class="main-bg">
    <header class="header-custom">
      <div class="logo-container">
        <img src="/logo-bg.jpg" alt="Logo Quilino Reyes" class="logo-header" />
      </div>
      <nav>
        <NuxtLink to="/">Inicio</NuxtLink> |
        <NuxtLink to="/modahombre">Moda Hombre</NuxtLink> |
        <NuxtLink to="/modamujer">Moda Mujer</NuxtLink> |
        <NuxtLink to="/corbatashombre">Corbatas Hombre</NuxtLink>
      </nav>
    </header>
    <main class="main-content">
      <NuxtPage />
    </main>
    <footer class="footer-custom">
      <p>&copy; 2025 Quilino Reyes · Moda Masculina</p>
    </footer>
  </div>
</template>

<style scoped>
.main-bg {
  min-height: 100vh;
  background: #181818 url('/logo-bg.jpg') repeat center center fixed;
  background-size: 450px auto;
  color: goldenrod;
  display: flex;
  flex-direction: column;
  min-width: 100vw;
  min-height: 100vh;
}
.main-content {
  flex: 1 1 auto;
  min-height: 1px;
  display: flex;
  flex-direction: column;
}
.header-custom {
  background: #181818;
  color: goldenrod;
  display: flex;
  flex-direction: row;
  align-items: center;
  border-bottom: 4px solid goldenrod;
  opacity: 0.97;
  height: 110px;
  min-height: 110px;
  justify-content: space-between;
  position: sticky;
  top: 0;
  z-index: 100;
}
.logo-container {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.logo-header {
  height: 100%;
  max-height: 110px;
  width: auto;
  object-fit: contain;
  display: block;
  border-radius: 10px;
  border: none;
}
nav {
  font-size: 1.3rem;
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
nav a {
  color: goldenrod;
  text-decoration: none;
  margin: 0 0.5rem;
  transition: color 0.2s;
}
nav a:hover {
  color: #fff;
}
.footer-custom {
  background: #181818;
  color: goldenrod;
  padding: 2rem 1rem 2rem 1rem;
  text-align: center;
  border-top: 4px solid goldenrod;
  margin-top: 0;
  opacity: 0.97;
  width: 100vw;
  position: static;
}
body, html, #__nuxt, #__layout {
  min-height: 100vh;
  height: 100%;
  margin: 0;
  padding: 0;
  border: none;
  box-sizing: border-box;
  background: #181818 !important;
}
</style>
