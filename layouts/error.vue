<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">Page not found : {{ error.statusCode }}</h1>
    <h1 v-else>An error occurred : {{ error.statusCode }}</h1>
    <NuxtLink to="/">Home page</NuxtLink>
  </div>
</template>

<script>
export default {
  props: ['error'],
  /**
   * 오류 페이지에대한 레이아웃 설정
   */
  // layout: 'blog'
};
</script>
