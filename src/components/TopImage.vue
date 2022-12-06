<template lang="pug">
#top-image
  //- router-link 路由之間切換
  //- router-link(to='/') 回根目錄 => 回首頁
  router-link(to='/')
    img(
      src='@/assets/logo.png' 
    alt='國立科技高中校園社團介紹網' 
    title='國立科技高中校園社團介紹網'
    )
</template>
