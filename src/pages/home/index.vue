<template>
  <app-page>
    <app-navbar title="首页" :left-arrow="false"></app-navbar>

    <text>首页</text>
    <nut-swiper
      :pagination-visible="true"
      pagination-color="#426543"
      pagination-unselected-color="#808080"
      auto-play="3000">
      <nut-swiper-item>
        <img src="https://storage.360buyimg.com/jdc-article/NutUItaro34.jpg" alt="" />
      </nut-swiper-item>
      <nut-swiper-item>
        <img src="https://storage.360buyimg.com/jdc-article/NutUItaro2.jpg" alt="" />
      </nut-swiper-item>
      <nut-swiper-item>
        <img src="https://storage.360buyimg.com/jdc-article/welcomenutui.jpg" alt="" />
      </nut-swiper-item>
      <nut-swiper-item>
        <img src="https://storage.360buyimg.com/jdc-article/fristfabu.jpg" alt="" />
      </nut-swiper-item>
    </nut-swiper>
    <app-tabbar active="home"></app-tabbar>
  </app-page>
</template>

<script lang="ts" setup>

</script>

<route type="home">
{ }
</route>