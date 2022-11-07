<style>
  p.view, footer {
    display: none;
  }
  .swiper-button-prev:after, .swiper-button-next:after {
    color: white; 
  }
  .swiper-pagination-bullet-active {
    background-color: white !important;
  }
</style>

<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"/>

<!-- Slider main container -->
<div class="swiper">
  <!-- Additional required wrapper -->
  <div class="swiper-wrapper">
    <!-- Slides -->
    <div class="swiper-slide">
      <img src="/spinners/assets/img/spinner.gif" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/1.jpeg" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/2.jpeg" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/3.jpeg" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/4.jpeg" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/5.jpeg" alt="" />
    </div>
    <div class="swiper-slide">
      <img src="/spinners/assets/img/6.jpeg" alt="" />
    </div>
  </div>
  <!-- If we need pagination -->
  <div class="swiper-pagination"></div>

  <!-- If we need navigation buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
</div>

<p>
  <small><i>Spinner based on <a href="https://www.thingiverse.com/thing:53451">Gear Bearing</a> by <a href="https://www.thingiverse.com/emmett/designs">Emmett Lalish</a>.</i></small>
  <small><i>Case based on <a href="https://www.printables.com/model/231874-triple-wall-twist-container-customizable">Triple-Wall Twist Container</a> by <a href="https://www.printables.com/social/253240-meshconnoisseur/about">meshconnoisseur</a>.</i></small><br>
</p>

<script src="//cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>

<!-- Initialize Swiper -->
<script>
  var swiper = new Swiper(".swiper", {
    effect: "fade",
    slidesPerView: 1,
    spaceBetween: 30,
    loop: true,
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    autoplay: {
      delay: 2500,
      disableOnInteraction: true,
    }
  });
  window.s = swiper;
</script>