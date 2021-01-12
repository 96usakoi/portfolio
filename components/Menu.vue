<template>
  <nav>
    <ul>
      <li>
        <NuxtLink to="/about">
          Menu link 1
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/illust">
          Menu link 2
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
