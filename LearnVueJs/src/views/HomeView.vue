<template>
  <div class="home-view">
    <h1>Vue.jsの紹介</h1>
    <img src="@/assets/logo.svg" alt="Vueのロゴ画像" />
    <p>
      Vue.jsは、人気のあるJavaScriptフレームワークです。
      <br />
      シンプルで柔軟なAPIを提供し、リアクティブなデータバインディングとコンポーネントベースのアーキテクチャを特徴としています。
    </p>
    <ul>
      <li>リアクティブなデータバインディング</li>
      <li>コンポーネントベースのアーキテクチャ</li>
      <li>シンプルで柔軟なAPI</li>
      <li>豊富なエコシステムとプラグイン</li>
    </ul>
    <p>
      Vue.jsは、単一ページアプリケーション（SPA）や複雑なフロントエンドプロジェクトの開発に適しています。
    </p>
    <br />
    <RouterLink to="/about">このサイトは何?</RouterLink>
    <OfficialLink />
  </div>
</template>
<style scoped>
.home-view {
  padding: 20px;
}

h1 {
  color: #42b983;
  font-size: 2rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.2rem;
  margin-bottom: 10px;
}

ul {
  list-style-type: disc;
  padding-left: 1.5rem;
}

li {
  font-size: 1rem;
  margin-bottom: 0.5rem;
}

img {
  width: 100px;
}
</style>

<script setup>
import OfficialLink from '@/components/OfficialLink.vue'
</script>
