<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="../assets/logo.jpg" alt="logo"></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link fw-bold" href="#">Menu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="#">News & Promo</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="#">FAQ</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="#">About Us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavbarView',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-link:hover {
  color: #e64227;
}

nav {
  padding-bottom: 15px !important;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}
</style>
