<template>
  <section class="container resume" id="education-experience">
    <!-- Title Section -->
    <div class="row">
      <h1 class="edu">Education & Experience</h1>
    </div>

    <!-- Timeline Section -->
    <div class="education container-fluid">
      <ul class="timeline">
        <li class="timeline-inverted">
          <div class="timeline-badge"></div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="timeline-title">Student</h4>
            </div>
            <div class="timeline-body">
              <p>Institution: Life Choices Academy</p>
              <p>Duration: 2024</p>
              <p>Full Stack Web Development Course</p>
            </div>
          </div>
        </li>
        <li>
          <div class="timeline-badge"></div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="timeline-title">Snr Associate Operations</h4>
            </div>
            <div class="timeline-body">
              <p>Company: WNS Global Services</p>
              <p>Duration: 2023</p>
              <p>Inbound & outbound calls to US customers. Creating endorsements for vehicles.</p>
            </div>
          </div>
        </li>
        <li class="timeline-inverted">
          <div class="timeline-badge"></div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="timeline-title">Customer Advisor</h4>
            </div>
            <div class="timeline-body">
              <p>Company: Sigma Connected</p>
              <p>Duration: 2021 - 2023</p>
              <p>Handling UK customer queries, providing solutions, and liaising with leadership.</p>
            </div>
          </div>
        </li>
        <li>
          <div class="timeline-badge"></div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="timeline-title">Sales Assistant</h4>
            </div>
            <div class="timeline-body">
              <p>Company: Sportsmans Warehouse</p>
              <p>Duration: 2019 - 2021</p>
              <p>Providing customer service, cleaning, and visual merchandising in the store.</p>
            </div>
          </div>
        </li>
        <li class="timeline-inverted">
          <div class="timeline-badge"></div>
          <div class="timeline-panel">
            <div class="timeline-heading">
              <h4 class="timeline-title">Student</h4>
            </div>
            <div class="timeline-body">
              <p>Institution: Steenberg High School</p>
              <p>Duration: 2014 - 2018</p>
              <p>Matric Certificate</p>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
/* Container and Basic Styles */
.resume {
  padding: 4rem 1.5rem;
  background-color: #f4f4f4; /* Light gray background for the section */
}

.edu {
  font-size: 2.5rem;
  text-align: center;
  color: #333;
  margin-bottom: 2rem;
}

/* Timeline Styles */
.timeline {
  position: relative;
  padding: 0;
  list-style: none;
  margin: 0;
}

.timeline::before {
  content: '';
  position: absolute;
  top: 0;
  bottom: 0;
  width: 4px;
  background: #007bff; /* Teal color for the timeline */
  left: 50%;
  margin-left: -2px;
}

/* Timeline Items */
.timeline > li {
  position: relative;
  margin-bottom: 50px;
}

.timeline > li::before {
  content: ' ';
  display: table;
}

.timeline > li::after {
  content: ' ';
  display: table;
  clear: both;
}

.timeline-inverted > .timeline-panel {
  float: right;
}

.timeline-badge {
  color: #fff;
  width: 50px;
  height: 50px;
  line-height: 50px;
  font-size: 1.4rem;
  text-align: center;
  position: absolute;
  top: 0;
  left: 50%;
  margin-left: -25px;
  background-color: #008080; /* Teal color for badges */
  border-radius: 50%;
  z-index: 100;
}

.timeline-panel {
  position: relative;
  width: 45%;
  padding: 20px;
  background: #ffffff; /* White background for panels */
  border-radius: 6px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.timeline-panel::before {
  content: "";
  position: absolute;
  top: 20px;
  width: 0;
  height: 0;
}

/* Arrow Styling */
.timeline-inverted > .timeline-panel::before {
  right: -15px;
  border-width: 10px 0 10px 15px;
  border-color: transparent transparent transparent #ffffff; /* Arrow color */
}

.timeline > li:not(.timeline-inverted) .timeline-panel::before {
  left: -15px;
  border-width: 10px 15px 10px 0;
  border-color: transparent #ffffff transparent transparent; /* Arrow color */
}

/* Headings */
.timeline-title {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
  color: #333;
}

/* Content Styles */
.timeline-body p {
  margin-bottom: 0.5rem;
  font-size: 1rem;
  color: #555;
}

/* Responsive Styling */
@media (max-width: 768px) {
  .timeline::before {
    left: 10px;
  }

  .timeline-badge {
    left: 10px;
    margin-left: 0;
  }

  .timeline-panel {
    width: 100%;
    padding-left: 60px;
  }

  .timeline-inverted .timeline-panel {
    float: none;
    padding-left: 60px;
  }

  .timeline-panel::before {
    left: 30px;
  }

  .timeline-inverted > .timeline-panel::before {
    right: auto;
    left: 30px;
    border-width: 10px 15px 10px 0;
    border-color: transparent #ffffff transparent transparent; /* Arrow color */
  }
}
</style>
