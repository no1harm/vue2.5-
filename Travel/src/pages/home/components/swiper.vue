<template>
    <div class="swiper">
    <swiper :options="swiperOption">
    <!-- slides -->
    <swiper-slide v-for="item of swiperList" :key="item.id">
        <img class="swiper-img" :src="item.imgUrl">
    </swiper-slide>
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
    </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [
        {
          id: '0001',
          imgUrl: 'https://img1.qunarzz.com/vc/29/31/b4/20fb7d1ad6e24362882319cbfb.jpg_750x388x92.jpg'
        },
        {
          id: '0002',
          imgUrl: 'https://img1.qunarzz.com/vc/31/cc/75/3c014d49de263aea6bf9bffeda.png'
        }
      ]
    }
  }
}
</script>
<style lang="stylus" scoped>
    .swiper-img
        width 100%
</style>
