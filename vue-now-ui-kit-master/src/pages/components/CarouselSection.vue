<template>
  <div id="carousel">
      <div class="row justify-content-center">
        <div class="col-12">
          <el-carousel height="800px">
            <el-carousel-item>
              <img class="d-block" src="img/bg1.png" alt="First slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>2016.07.23</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/bg2.png" alt="rond slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>2017.07.23</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/bg3.png" alt="Third slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>2018.07.23&2019.07.23</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/bg4.png" alt="Fourth slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>2020.07.23</h5>
              </div>
            </el-carousel-item>
          </el-carousel>
        </div>
      </div>
  </div>
</template>
<script>
import { Carousel, CarouselItem } from 'element-ui';

export default {
  components: {
    [Carousel.name]: Carousel,
    [CarouselItem.name]: CarouselItem
  }
};
</script>
<style></style>
