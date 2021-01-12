<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
      nyan nyan🐱
      </h1>

      <div>
        <Menu />
      </div>
      <figure class="bg-gray-100 rounded-xl p-8">
        <img class="w-32 h-32 s-full mx-auto" style="background:#000;" src="/test.jpg" alt="" width="384" height="512">
        <div class="pt-6 text-center space-y-4">
          <blockquote>
            <p class="text-lg font-semibold">
              text
            </p>
          </blockquote>
          <figcaption class="font-medium">
            <div class="text-cyan-600">
              niku
            </div>
            <div class="text-gray-500">
              niku
            </div>
          </figcaption>
        </div>
      </figure>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
