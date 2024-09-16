<template>
  <div class="container landing">
    <div class="row vh-100 align-items-center">
      <div class="col-md-4">
        <img src="https://asheekasamuels.github.io/All-Images/images/Asheeka1.jpg" alt="Asheeka1" class="img-fluid w-100 mb-5" loading="lazy">
      </div>
      <div class="col">
        <div id="details">
          <h1 class="typewriter">Asheeka Samuels</h1>
          <p class="typewriter-sub" v-if="title !== null">I am an <span>{{ title.toString() }}</span></p>
          <Spinner v-else />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Spinner from './Spinner.vue';
import { computed, onMounted } from 'vue';
import { useStore } from 'vuex';

const store = useStore();
const title = computed(() => store.state.title);

onMounted(() => {
  store.dispatch('fetchTitle');
});
</script>

<style scoped>
/* Global styles */
body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f9; /* Light background for a modern look */
}

/* Landing Page Styles */
.landing {
  padding: 2rem;
}

h1.typewriter {
  font-size: 3rem; /* Larger font size for the main title */
  color: #333; /* Dark text color for contrast */
  text-align: left; /* Align text to the left */
  margin-bottom: 1rem; /* Space below the title */
  position: relative; /* For adding a typewriter effect */
}

h1.typewriter::after {
  content: '';
  display: block;
  width: 100%;
  height: 5px;
  background-color: #007bff; /* A bright accent color */
  position: absolute;
  bottom: -5px; /* Positioning below the text */
  left: 0;
  animation: blink 1s infinite; /* Blink animation for a modern touch */
}

@keyframes blink {
  0%, 100% { opacity: 0; }
  50% { opacity: 1; }
}

.typewriter-sub {
  font-size: 1.5rem; /* Slightly larger font for the subtitle */
  color: #666; /* Gray color for subtler contrast */
  margin-top: 0.5rem; /* Space above the subtitle */
}

/* Image styling */
.img-fluid {
  border-radius: 15px; /* Rounded corners for a softer look */
  box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

/* Spinner styles */
.spinner {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100px; /* Adjust height for the spinner */
}
</style>

  