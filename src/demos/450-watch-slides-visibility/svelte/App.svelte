<script>
  import { Swiper, SwiperSlide } from "swiper/svelte";

  // Import Swiper styles
  import "swiper/css";

  import "./style.css";
</script>

<h3>
  Slider5 is visible when you slide to 2,3, or 4, and slider5 has
  "swiper-slide-visible" className
</h3>
<br />
<Swiper watchSlidesProgress={true} slidesPerView={3} class="mySwiper">
  <SwiperSlide>Slide 1</SwiperSlide><SwiperSlide>Slide 2</SwiperSlide
  ><SwiperSlide>Slide 3</SwiperSlide><SwiperSlide>Slide 4</SwiperSlide
  ><SwiperSlide>Slide 5</SwiperSlide><SwiperSlide>Slide 6</SwiperSlide
  ><SwiperSlide>Slide 7</SwiperSlide><SwiperSlide>Slide 8</SwiperSlide
  ><SwiperSlide>Slide 9</SwiperSlide>
</Swiper>
