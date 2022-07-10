<script setup lang="ts">
import { RouterView } from "vue-router";
</script>

<template>
  <RouterView />

  <footer class="footer">
    <div class="beian">
      <a href="https://beian.miit.gov.cn/" target="_blank"
        >陕ICP备20011829号-1</a
      >
      <a
        href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=61019002001182"
        target="_blank"
        >陕公安网备61019002001182号</a
      >
    </div>
  </footer>
</template>

<style>
body {
  margin: 0;
  overflow-x: hidden;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  min-width: 375px;
  width: 100%;
  background: #040d21;
}

.footer {
  height: 2rem;
}

.beian {
  display: flex;
  align-items: center;
  gap: 20px;
  height: 2rem;
}

.beian a {
  font-size: 0.5rem;
  color: #6e7e9b;
  text-decoration: none;
}

.beian a:hover {
  color: #8192b1;
}
</style>
