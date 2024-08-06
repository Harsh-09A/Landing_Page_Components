# Sliders / Banner Section

## Slider 1 :-

### HTML

![Slider_1](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

```
<!-- Slider Section -->
<section id="slider_section">
  <!--  Slider -->
  <div
    id="carousel-Indicators"
    class="carousel slide desktop-slider"
    data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carousel-Indicators"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"></button>
      <button
        type="button"
        data-bs-target="#carousel-Indicators"
        data-bs-slide-to="1"
        aria-label="Slide 2"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          class="d-block w-100 banner1"
          width="100%"
          src="img/banners/desktop_banner1.webp"
          alt="Banner1" />
      </div>
      <div class="carousel-item">
        <img
          class="d-block w-100 banner2"
          width="100%"
          src="img/banners/desktop_banner2.webp"
          alt="Banner2" />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carousel-Indicators"
      data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carousel-Indicators"
      data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</section>
<!-- Slider Section Ends -->


```
