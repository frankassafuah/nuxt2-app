<template>
  <div>
    <nav class="navbar navbar-expand-lg navar-light bg-white shadow">
      <div class="container">
        <NuxtLink to="/" class="navbar-brand">
          <img class="logo-img" src="/images/image-from-rawpixel-id-3150659-original.png" alt="">
        </NuxtLink>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <NuxtLink to="/" class="nav-link">Home</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/about" class="nav-link">About Us</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/services" class="nav-link">Our Services</NuxtLink>
            </li>
            <li class="nav-item">
              <NuxtLink to="/contact" class="nav-link">Contact Us</NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>
<style>
.logo-img {
  width: 35px;
}
</style>
