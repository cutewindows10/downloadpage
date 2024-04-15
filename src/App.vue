<template>
  <div class="app-container h-screen flex flex-col items-center justify-center bg-gray-900 text-white">
    <div class="app-content max-w-md text-center space-y-8">
      <div class="app-logo">
        <img src="./assets/logo.png" alt="App Logo" class="w-24 h-24 md:w-32 md:h-32 mx-auto">
      </div>
      <div class="app-title text-2xl md:text-3xl font-bold">
        白竜
      </div>
      <div class="app-description text-gray-400 text-sm md:text-base">
        Hidden Studio for kawaii fake nerds
      </div>
      <DownloadApp />
    </div>
  </div>
</template>

<script>
import DownloadApp from './components/DownloadApp.vue';

export default {
  name: 'App',
  components: {
    DownloadApp,
  },
};
</script>