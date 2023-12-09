<template>
  <div id="imageCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../assets/slide-one.jpeg" class="d-block w-100" alt="Image 1" height="400">
      </div>
      <div class="carousel-item">
        <img src="../assets/slide-two.jpeg" class="d-block w-100" alt="Image 2">
      </div>
      <div class="carousel-item">
        <img src="../assets/slide-three.jpg" class="d-block w-100" alt="Image 3">
      </div>
    </div>
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-bs-target="#imageCarousel" data-bs-slide-to="0" class="active"></li>
      <li data-bs-target="#imageCarousel" data-bs-slide-to="1"></li>
      <li data-bs-target="#imageCarousel" data-bs-slide-to="2"></li>
    </ol>
  </div>
  <i class="bi bi-person-hearts h1"></i>
  <figure class="text-center">
    <blockquote class="blockquote">
      <p class="fw-bold h1">Choose Your Moment</p>
    </blockquote>
    <figcaption class="blockquote-footer">
      Breads for every occasions
    </figcaption>
  </figure>
</template>

<script>
export default {
  name: 'SiderView',
}
</script>

<style scoped>
i {
  line-height: 4;
  color: #e64227;
}

/* Adjust styles for indicators */
.carousel-indicators {
  position: absolute;
  bottom: 0;
  left: 35%;
  transform: translateX(-50%);
}

.carousel-indicators li {
  background-color: #d5d5d5;
  border-radius: 50%;
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 0 5px;
  cursor: pointer;
}

.carousel-indicators .active {
  background-color: #555;
}
</style>
