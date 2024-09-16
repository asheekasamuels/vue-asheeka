<template>
  <section class="projects-section">
    <div class="container">
      <h2 class="section-title">Projects</h2>

      <div class="projects-grid">
        <!-- Capstone Project -->
        <div class="project-card">
          <h3 class="project-title">Capstone Project</h3>
          <p class="project-description">
            A web application designed to [Brief description of your Capstone project].
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> HTML, CSS, JavaScript, Vue.js
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>

        <!-- Other Projects -->
        <div class="project-card">
          <h3 class="project-title">Project 1</h3>
          <p class="project-description">
            [Brief description of Project 1]
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> React, Node.js, MongoDB
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>

        <div class="project-card">
          <h3 class="project-title">Project 2</h3>
          <p class="project-description">
            [Brief description of Project 2]
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> Vue.js, Firebase
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>

        <div class="project-card">
          <h3 class="project-title">Project 3</h3>
          <p class="project-description">
            [Brief description of Project 3]
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> Python, Django
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>

        <div class="project-card">
          <h3 class="project-title">Project 4</h3>
          <p class="project-description">
            [Brief description of Project 4]
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> Python, Django
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>

        <div class="project-card">
          <h3 class="project-title">Project 5</h3>
          <p class="project-description">
            [Brief description of Project 5]
          </p>
          <p class="project-technologies">
            <strong>Technologies used:</strong> Python, Django
          </p>
          <div class="project-links">
            <a href="#" class="btn" target="_blank">GitHub Repository</a>
            <a href="#" class="btn" target="_blank">Live Demo</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Section Styling */
.projects-section {
  padding: 4rem 0;
  background-color: #f4f4f4; /* Light gray background */
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

/* Section Title */
.section-title {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

/* Projects Grid */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
}

/* Project Card Styling */
.project-card {
  background-color: #ffffff; /* White background for cards */
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.project-card:hover {
  transform: translateY(-5px);
}

/* Project Title */
.project-title {
  font-size: 1.8rem;
  color: #333;
  margin-bottom: 1rem;
}

/* Project Description */
.project-description {
  color: #555; /* Slightly lighter text for description */
  margin-bottom: 1rem;
}

/* Technologies Used */
.project-technologies {
  font-size: 1rem;
  color: #333;
  margin-bottom: 1.5rem;
}

/* Project Links */
.project-links {
  display: flex;
  justify-content: space-between;
}

/* Button Styling */
.btn {
  padding: 0.75rem 1.5rem;
  font-size: 1rem;
  border: none;
  border-radius: 6px;
  text-align: center;
  cursor: pointer;
  text-decoration: none;
  color: white;
}

.btn:first-child {
  background-color: #008080; /* Teal color for GitHub Repository */
}

.btn:last-child {
  background-color: #ff6f61; /* Coral color for Live Demo */
}

.btn:hover {
  opacity: 0.9;
}

/* Responsive Design */
@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr; /* Stack cards on smaller screens */
  }
}
</style>

  