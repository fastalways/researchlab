<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="200"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <a href="./">
        <b-carousel-slide
          caption="Hydra Research Lab"
          text="Hydra Research Lab, Computer Engineering, Faculty of Engineering, Rajamangala University of Technology Srivijaya"
          img-src="https://picsum.photos/1024/480/?image=52"
        />
      </a>

      <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
        <h1>Welcome to Hydra Research Lab, Smart Digital Innovation Lab</h1>
      </b-carousel-slide>

      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <b-carousel-slide>
        <template #img>
          <img
            class="d-block img-fluid w-100"
            width="1024"
            height="480"
            src="~/assets/img/dept_coe.jpg"
            alt="image slot"
          >
        </template>
      </b-carousel-slide>

      <b-carousel-slide caption="กลุ่มวิจัยไฮดร้า" img-blank>
        <p>
          วิศวกรรมคอมพิวเตอร์, คณะวิศวกรรมศาสตร์, มหาวิทยาลัยเทคโนโลยีราชมงคลศรีวิชัย
        </p>
      </b-carousel-slide>
    </b-carousel>

    <!-- <p class="mt-4">
      Slide #: {{ slide }}<br>
      Sliding: {{ sliding }}
    </p> -->
  </div>
</template>

<script>
export default {
  data () {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart (slide) {
      this.sliding = true
    },
    onSlideEnd (slide) {
      this.sliding = false
    }
  }
}
</script>

<style>
    .carousel-item img {
        height:30vh!important ;
    }
</style>
