<template>
  <div class="page-about">
    <h1>About</h1>
    <p>これは Nuxt 4 のサンプルプロジェクトです。</p>
    <p>DevContainer で動作しています。</p>
    <NuxtLink to="/" class="back-link">← トップに戻る</NuxtLink>
  </div>
</template>

<style scoped>
.page-about {
  text-align: center;
  padding: 2rem 0;
}

h1 {
  color: #00dc82;
  margin-bottom: 1rem;
}

p {
  color: #666;
  margin-bottom: 0.5rem;
}

.back-link {
  display: inline-block;
  margin-top: 2rem;
  color: #00dc82;
  font-weight: bold;
}

.back-link:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  h1 {
    font-size: 1.5rem;
  }
}
</style>
