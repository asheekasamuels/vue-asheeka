<template>
    <footer class="container-fluid">
      <div class="row">
        <!-- Center: Span element -->
        <div class="col-md-4 text-center">
          <p class="lead text-black">
            <span>Asheeka Samuels Portfolio</span>
            <span> &copy; 2024</span>
          </p>
        </div>
      </div>
    </footer>
  </template>

<script>
export default {
    name: "FooterComp",
    data() {
        return {
            currentYear: new Date().getUTCFullYear()

        }
    },
    mounted() {

    }
}
</script>

<style>

</style>