<template>
  <div class="container relative">
    <div>
      <h1 class="title">
      about
      </h1>

      <div>
        <Menu />
      </div>

    <figure class="my-10 md:flex bg-gray-100 rounded-xl p-8 md:p-0 border-solid border-2 border-gray-50 overflow-hidden">
      <img class="p-2 w-32 h-32 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto bg-white" src="@/assets/images/common/profile.jpg" alt="" width="384" height="512">
        <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
          <blockquote>
            <p class="text-lg font-semibold">
              Iori Nakaji
            </p>
            <p class="text-gray-500 text-xs">
              @96usa_koi
            </p>
          </blockquote>
          <figcaption class="font-medium">
            <div class="text-cyan-600 text-sm">
              Webデザイナー
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
