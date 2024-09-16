<template>
  <div class="about container">
    <!-- About Me Section -->
    <div class="content-wrapper">

      <!-- Text Section -->
      <div class="text-wrapper text-center"> <!-- Added text-center class -->
        <h1 class="heading">About Me</h1>
        <p class="lead">
          Born 23rd April 2001, in the lovely city of Cape Town - I am a seasoned worker who has used my experience in the industry to develop a leadership brand that precedes myself. I am trusted by my peers and senior leadership because of my consistent commitment to go beyond expectations.
        </p>
        <p class="lead">
          My team engagement is admirable, and my greatest strength is my ability to build genuine trust relationships with all my peers. I have backbone, and I am vocal about my opinions, always in the best way possible.
        </p>
        <p class="lead">
          I am emotionally balanced and always approach situations with an open mind. I strive to operate in the best interest of the business while factoring in the human elements that contribute to every scenario.
        </p>
        <p class="lead">
          Both an introvert and an extrovert, I love being in the kitchen trying new recipes, going on hikes, and attending festivals. Just a few random things for you to know about me. Hope you enjoy my portfolio.
        </p>

        <!-- Technical Skills Section with Icons -->
        <h2 class="sub-heading">Technical Skills</h2>
        <div class="skills-grid">
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-node-js-128.png" alt="JavaScript-Icon" class="skill-icon">
            <p>JavaScript</p>
          </div>
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-html-150 (1).png" alt="HTML-Icon" class="skill-icon">
            <p>HTML5</p>
          </div>
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-css-150 (1).png" alt="CSS-Icon" class="skill-icon">
            <p>CSS3</p>
          </div>
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-vuejs-128.png" alt="Vue.js-Icon" class="skill-icon">
            <p>Vue.js</p>
          </div>
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-bootstrap-150 (1).png" alt="Bootstrap" class="skill-icon">
            <p>Bootstrap</p>
          </div>
          <div class="skill-item">
            <img src="https://github.com/asheekasamuels/All-Images/images/icons8-wordpress-150-1.png" alt="Wordpress" class="skill-icon">
            <p>Wordpress</p>
          </div>
        </div>
        <img src="https://github.com/asheekasamuels/All-Images/images/icons8-figma-150-1 (1).png" alt="Figma-Icon" class="skill-icon"> 
        <p>Figma</p>

        <!-- Soft Skills Section with Icons -->
        <h2 class="sub-heading">Soft Skills</h2>
        <div class="skills-grid">
          <div class="skill-item">
            <img src="https://example.com/icons/communication.png" alt="Communication Icon" class="skill-icon">
            <p>Communication</p>
          </div>
          <div class="skill-item">
            <img src="https://example.com/icons/problem-solving.png" alt="Problem Solving Icon" class="skill-icon">
            <p>Problem Solving</p>
          </div>
          <div class="skill-item">
            <img src="https://example.com/icons/teamwork.png" alt="Teamwork Icon" class="skill-icon">
            <p>Teamwork</p>
          </div>
          <div class="skill-item">
            <img src="https://example.com/icons/time-management.png" alt="Time Management Icon" class="skill-icon">
            <p>Time Management</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
* {
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f9f9f9;
  color: #333;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}

.content-wrapper {
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  padding: 40px;
  text-align: center; /* Center all text within the content wrapper */
}

.heading {
  font-size: 2.5em;
  margin-bottom: 20px;
  color: #1a1a1a;
}

.lead {
  font-size: 1.1em;
  line-height: 1.6;
  margin: 10px 0;
}

.sub-heading {
  font-size: 1.8em;
  margin-top: 30px;
  margin-bottom: 10px;
  color: #333;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.skill-item {
  text-align: center;
}

.skill-icon {
  width: 50px;
  height: 50px;
  margin-bottom: 10px;
}

.skill-item p {
  font-size: 1em;
  color: #666;
  margin: 0;
}
</style>
