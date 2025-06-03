<script setup></script>
<template>
<div>
  <h1>Bienvenido a la Página Principal</h1>
  <p>Esta es la página principal de nuestro sitio web. Aquí puedes encontrar enlaces a diferentes secciones.</p>
  <ul>
    <li>
      <NuxtLink to="/modamujer">Moda Mujer</NuxtLink>
    </li>
    <li>
      <NuxtLink to="/corbatashombre">Corbatas Hombre</NuxtLink>
    </li>
  </ul>
  <slot />
</div>
</template>