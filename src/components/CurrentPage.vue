<template>
  <div class="carousel">
    <div class="swiper-container" ref="mySwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="(image, index) in images" :key="index">
          <img :src="require(`@/assets/${image}`)" alt="Image" class="carousel-image" />
        </div>
      </div>
    </div>
    <div class="swiper-button-prev" @click="prevPage"></div>
    <div class="swiper-button-next" @click="nextPage"></div>
    <div class="custom-pagination">
      <div
        class="pagination-item"
        v-for="(image, index) in images"
        :key="index"
        :class="{ 'active': index === currentPage }"
      ></div>
    </div>
  </div>
</template>

<script>
import Swiper from 'swiper';
import 'swiper/swiper-bundle.css'; // Import Swiper styles

export default {
  data() {
    return {
      images: [
        'DC.webp',
        'wp1867294-john-wick-wallpapers.jpg',
        'wp2028630-dr-strange-wallpapers.jpg',
        '198608.jpg',
      ],
      mySwiper: null,
      currentPage: 0,
    };
  },
  mounted() {
    this.initSwiper();
  },
  methods: {
    initSwiper() {
      this.mySwiper = new Swiper(this.$refs.mySwiper, {
        // Configuration options go here
        centeredSlides: true,
        spaceBetween: 40,
        slidesPerView: 1.4,
        loop: true,
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
      });
      this.mySwiper.on('slideChange', () => {
        this.currentPage = this.mySwiper.realIndex;
      });
    },
    nextPage() {
      this.mySwiper.slideNext();
    },
    prevPage() {
      this.mySwiper.slidePrev();
    },
  },
};
</script>

<style scoped>
.carousel {
  position: relative;
  overflow: hidden;
  text-align: center;
}

.carousel-image {
  width: 900px;
  height: 450px;
  border-radius: 15px;
}

.custom-pagination {
  display: flex;
  justify-content: center;
  margin-top: 10px;
}

.pagination-item {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: white;
  margin: 0 5px;
}

.pagination-item.active {
  background-color: #007BFF;
}
</style>
