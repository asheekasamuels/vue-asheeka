<template>
  <nav class="navbar navbar-expand-lg sticky-top">
    <div class="container-fluid">
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
        <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" href="#landing">Home</a>
          </li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item">
            <a class="nav-link" href="#resume">Education & Experience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact Me</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBarComp",
};
</script>

<style scoped>
img[alt="logo"] {
  width: 80px;
  height: 80px;
}
.navbar-nav {
  text-align: center; /* Ensures the text aligns in the center */
  margin: 2 auto;
  padding: 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.container-fluid {
  padding: 0;
  height: 100px;
}
</style>
