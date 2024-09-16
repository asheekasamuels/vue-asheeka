<template>
  <div class="container contact">
    <!-- Contact Heading -->
    <div class="row">
      <h1 class="contact1">Contact Me</h1>
    </div>

    <div class="contact-content">
      <!-- Contact Form -->
      <form action="https://formspree.io/f/mrgnjjvw" method="POST" class="contact-form">
        <div class="form-group">
          <label for="name">Your Full Name *</label>
          <input type="text" id="name" name="name" placeholder="Your Full Name" required>
        </div>

        <div class="form-group">
          <label for="email">Valid Email Address *</label>
          <input type="email" id="email" name="email" placeholder="Valid Email Address" required>
        </div>

        <div class="form-group">
          <label for="contact">Mobile / Telephone Number *</label>
          <input type="tel" id="contact" name="contact" placeholder="Mobile / Telephone Number" required>
        </div>

        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" name="message" rows="5" placeholder="Let us know how we can help!"></textarea>
        </div>

        <p>* indicates a required field</p>

        <div class="form-actions">
          <button type="submit" class="btn-primary">Submit</button>
          <button type="reset" class="btn-secondary">Reset</button>
        </div>
      </form>

      <!-- Contact Details -->
      <div class="contact-details">
        <h2>Contact Details</h2>
        <p><strong>Email:</strong> your.email@example.com</p>
        <p><strong>Phone:</strong> (123) 456-7890</p>
        
        <h2>Follow Me</h2>
        <div class="social-links">
          <a href="#" class="social-link">LinkedIn</a>
          <a href="#" class="social-link">GitHub</a>
          <a href="#" class="social-link">Twitter</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Basic Container Styling */
.contact {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

h1.contact1 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #333;
}

/* Contact Content Layout */
.contact-content {
  display: flex;
  justify-content: space-between;
}

/* Form Styling */
.contact-form {
  background-color: #f9f9f9;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  flex: 1;
  margin-right: 2rem;
}

.contact-details {
  flex: 1;
  background-color: #f4f4f4; /* Light gray for contrast */
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

/* Form Group */
.form-group {
  margin-bottom: 1.5rem;
}

label {
  font-size: 1rem;
  color: #333;
  margin-bottom: 0.5rem;
  display: block;
}

input, textarea {
  width: 100%;
  padding: 0.75rem;
  border: 1px solid #ccc;
  border-radius: 6px;
  font-size: 1rem;
  color: #333;
}

input:focus, textarea:focus {
  outline: none;
  border-color: #008080; /* Teal color */
  box-shadow: 0 0 5px rgba(0, 128, 128, 0.5);
}

textarea {
  resize: vertical;
}

/* Form Action Buttons */
.form-actions {
  display: flex;
  justify-content: space-between;
  margin-top: 1.5rem;
}

.btn-primary, .btn-secondary {
  padding: 0.75rem 1.5rem;
  font-size: 1rem;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

.btn-primary {
  background-color: #008080; /* Teal color */
  color: white;
}

.btn-secondary {
  background-color: #6c757d;
  color: white;
}

.btn-primary:hover {
  background-color: #006d68;
}

.btn-secondary:hover {
  background-color: #5a6268;
}

/* Contact Details */
.contact-details h2 {
  margin-top: 0;
  font-size: 1.5rem;
  color: #333;
}

.contact-details p {
  color: #333;
}

.social-links {
  margin-top: 1rem;
}

.social-link {
  margin-right: 1rem;
  color: #008080; /* Teal color */
  text-decoration: none;
}

.social-link:hover {
  text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
  .contact-content {
    flex-direction: column;
  }

  .contact-form {
    margin-right: 0;
    margin-bottom: 2rem;
  }

  .form-actions {
    flex-direction: column;
    align-items: center;
  }

  .btn-primary, .btn-secondary {
    width: 100%;
    margin-bottom: 1rem;
  }
}
</style>

