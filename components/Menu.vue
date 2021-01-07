<template>
  <nav>
    <ul>
      <li>
        <NuxtLink to="/about">
          About
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/illust">
          Illust
        </NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
