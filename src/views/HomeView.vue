<script setup lang="ts">
import avatar from "@/assets/images/avatar.png";
</script>

<template>
  <main class="main">
    <div class="container">
      <h1 class="subject">星海昔织</h1>
      <img :src="avatar" class="avatar" alt="" />
      <p class="mission">分享IT思维，学习经验交流</p>
      <p class="soon">comming soon...</p>
    </div>
  </main>
</template>

<style>
.main {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  gap: 20px;
}

.subject {
  font-size: 5rem;
  font-weight: 400;
  color: rgb(118, 184, 250);
  display: flex;
  justify-content: space-around;
  padding: 0;
  margin: 0;
  background: linear-gradient(218.9deg, #a2facf 20.19%, #64acff 79.81%);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.avatar {
  width: 100px;
  height: 100px;
  border-radius: 100%;
}

.mission {
  color: #8192b1;
  font-size: 1.1rem;
}

.soon {
  color: #6e7e9b;
}
</style>
