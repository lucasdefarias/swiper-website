<script>
  import { Swiper, SwiperSlide } from "swiper/svelte";

  // Import Swiper styles
  import "swiper/css";

  import "swiper/css/grid";
  import "swiper/css/pagination";

  import "./style.css";

  // import required modules
  import { Grid, Pagination } from "swiper";
</script>

<Swiper
  slidesPerView={3}
  grid={{
    rows: 2,
  }}
  spaceBetween={30}
  pagination={{
    clickable: true,
  }}
  modules={[Grid, Pagination]}
  class="mySwiper"
>
  <SwiperSlide>Slide 1</SwiperSlide><SwiperSlide>Slide 2</SwiperSlide
  ><SwiperSlide>Slide 3</SwiperSlide><SwiperSlide>Slide 4</SwiperSlide
  ><SwiperSlide>Slide 5</SwiperSlide><SwiperSlide>Slide 6</SwiperSlide
  ><SwiperSlide>Slide 7</SwiperSlide><SwiperSlide>Slide 8</SwiperSlide
  ><SwiperSlide>Slide 9</SwiperSlide>
</Swiper>
