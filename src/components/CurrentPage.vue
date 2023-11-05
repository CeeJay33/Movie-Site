<template>
    <div class="carousel">
      <div class="carousel-container" :style="{ transform: `translateX(${translateX}px)` }">
        <div class="carousel-item" v-for="(image, index) in images" :key="index">
          <img :src="require(`@/assets/${image}`)" alt="Image" />
        </div>
      </div>
      <i class="fa fa-chevron-left arrow left" @click="prevPage"></i>
      <i class="fa fa-chevron-right arrow right" @click="nextPage"></i>
    </div>
  </template>
  
  <script>

  export default {
    data() {
      return {
        images: [
          'DC.webp',
          'DC.webp',
          'DC.webp',
        ],
        currentPage: 0,
        translateX: 0,
      };
    },
    methods: {
      nextPage() {
        if (this.currentPage < this.images.length - 1) {
          this.currentPage++;
          this.translateX -= 400;
        }
      },
      prevPage() {
        if (this.currentPage > 0) {
          this.currentPage--;
          this.translateX += 400;
        }
      },
    },
  };
  </script>
  
  <style>
body{
    background-color:  #18181b;
}
  .carousel {
    display: flex;
    align-items: center;
    overflow: hidden;
    position: relative;
  }
  
  .carousel-container {
    display: flex;
    justify-content: center;
    align-items: centers;
    gap: 1rem;
    transition: transform 0.3s ease-in-out;
  }
  
  .carousel-item {
    flex-shrink: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 350px;
  }
  
  .carousel-item img {
    max-height: 100%;
    border-radius: 15px;
  }
  
  .arrow {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    cursor: pointer;
  }
  
  .left {
    left: 10px;
  }
  
  .right {
    right: 10px;
  }
  </style>
  