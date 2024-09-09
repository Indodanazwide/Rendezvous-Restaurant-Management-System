<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="layout">
    <header>
      <!-- Navbrand logo -->
      <img
        src="@/assets/images/png/brand-logo.png"
        alt="Rendezvous Restaurant"
        class="navbar-brand-logo"
      />

      <!-- Navigation -->
      <nav>
        <ul>
          <li><RouterLink to="/">Home</RouterLink></li>
          <li><RouterLink to="/menu">Menu</RouterLink></li>
          <li><RouterLink to="/about">About</RouterLink></li>
          <li><RouterLink to="/contact">Contact</RouterLink></li>
        </ul>

        <ul class="management-links">
          <li>
            <a href="#">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-person-fill"
                viewBox="0 0 16 16"
              >
                <path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6" />
              </svg>
            </a>
          </li>
          <li>
            <a href="#">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-basket-fill"
                viewBox="0 0 16 16"
              >
                <path
                  d="M5.071 1.243a.5.5 0 0 1 .858.514L3.383 6h9.234L10.07 1.757a.5.5 0 1 1 .858-.514L13.783 6H15.5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H15v5a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V9H.5a.5.5 0 0 1-.5-.5v-2A.5.5 0 0 1 .5 6h1.717zM3.5 10.5a.5.5 0 1 0-1 0v3a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 1 0-1 0v3a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 1 0-1 0v3a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 1 0-1 0v3a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 1 0-1 0v3a.5.5 0 0 0 1 0z"
                />
              </svg>
            </a>
          </li>
          <li class="nav-cta-btn"><a href="#">Book A Table</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <RouterView />
    </main>

    <footer>
      <section class="upper-footer-section">
        <article class="about-us-footer">
          <h3>Rendezvous Restaurant</h3>

          <p>The Hotel School Restaurant is available for lunch or dinner by prior booking. Our intention is to provide attentive service and high-quality food, both in taste and appearance, at a competitive price.</p>
            <p>The menu will be designed to suit your requirements, and complementary wines will be recommended. A full bar is also available for pre-meal drinks in relaxing surroundings.</p>
            <p>Food preparation and service is handled by Hotel School students under the guidance of experienced chef lecturers.</p>
            <p>
              <strong>For bookings and more information:</strong><br>
              Ms Joanne Mjoka (Email: <a href="mailto:JoanneM@dut.ac.za">JoanneM@dut.ac.za</a>, Tel: 031 373 5526)
            </p>
        </article>

        <article class="contact-info-footer">
          <div>
            <h3>Rendezvous Restaurant</h3>
            <p>Rendezvous Restaurant is run by students from the Department of Food and Nutrition Consumer Science.</p>
            <p>
              <strong>Location:</strong> Steve Biko Campus, Block S9, Level 4
            </p>
            <p>
              <strong>Operating times:</strong><br>
              Wednesdays and Thursdays from 11:00 to 14:00 (first semester)<br>
              Wednesdays, Thursdays, and Fridays from 11:00 to 14:00 (second semester)
            </p>
            <p>The students prepare and serve a variety of meals, sweet treats, and beverages. Vegetarian options are available.</p>
            <p>We can also assist with your function planning requirements.</p>
            
          </div>
        </article>
        

        <article class="feedback-form-footer">
          
          <h3>Send Us a Feedback</h3>

          <form action="" method="post">
            <input type="text" name="Name" id="eame" placeholder="Name" />
            <input type="email" name="Email" id="email" placeholder="Email" />
            <textarea name="Message" id="Message" placeholder="Message"></textarea>

            <button type="submit">Send</button>
          </form>

          <article class="quick-links">
            <br>
            <h3>Quick Links</h3>
            <ul>
              <li><RouterLink to="/">Home</RouterLink></li>
              <li><RouterLink to="/menu">Menu</RouterLink></li>
              <li><RouterLink to="/about">About</RouterLink></li>
              <li><RouterLink to="/contact">Contact</RouterLink></li>
            </ul>
          </article>
        </article>
      </section>

      <section class="middle-footer-section" style="width: 100%; text-align: center; margin: 0;">
        <p>
          <strong>For reservations and enquiries, contact:</strong><br>
          Jane Visagie (Email: <a href="mailto:janev@dut.ac.za">janev@dut.ac.za</a>, Tel: 031 373 2383)<br>
          Jabu Chiya (Tel: 031 373 6695)<br>
          Noxolo Blose (Tel: 031 373 2322)
        </p>
      </section>

      <hr />

      <section class="lower-footer-section">
        <p>&copy; 2024 Rendezvous Restaurant. All rights reserved.</p>
      </section>
    </footer>
  </div>
</template>

<style scoped>
/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  top: 0;
  z-index: 1000;
  width: 100%;
  height: 15vh;
  padding: 2rem 4rem;
  background-color: whitesmoke;
  box-shadow: 10px 5px 5px rgba(rgb(180, 180, 180), rgb(71, 71, 71), rgb(44, 44, 44), alpha);
}

.navbar-brand-logo {
  width: 3.5rem;
}

nav,
nav ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-inline: 2rem;
}

nav ul li {
  margin-inline: 1rem;
}

.nav-cta-btn a {
  background-color: #93759c;
  padding: 0.8rem 1.2rem;
  border-radius: 3rem;
  text-transform: uppercase;
  letter-spacing: 0.1rem;
  transition: 0.3s;
}

.nav-cta-btn a:hover {
  background-color: rgb(202, 202, 202);
}

nav a {
  color: #0f152c;
}

nav a:hover {
  color: #63B375;
}

/* Main */


/* Footer */
footer {
  background-color: #0f152c;
  color: #b5a4a9;
  padding: 2rem 1rem;
  position: relative;
}

.upper-footer-section {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 2rem;
}

.upper-footer-section article {
  flex: 1 1 200px;
  margin: 2rem 1rem 0;
}

footer h3 {
  font-size: 1.5rem;
  color: #b2a43b;
  margin-bottom: 1rem;
  position: relative;
}

footer h3:after {
  content: '';
  display: block;
  width: 4rem;
  height: 0.3rem;
  background-color: #b2a43b;
  margin-top: 1rem;
}

footer p,
footer li,
footer a {
  font-size: 1rem;
  line-height: 1.6;
}

.about-us-footer p {
  font-style: italic;
  color: #b5a4a9;
}

.quick-links ul li {
  margin-bottom: 1rem;
}

.quick-links ul li a {
  text-decoration: none;
  color: #b5a4a9;
  transition: color 0.3s;
}

.quick-links ul li a:hover {
  color: #b2a43b;
}

.contact-info-footer p {
  margin: 1rem 0;
}

.contact-info-footer a {
  color: #b2a43b;
}

.contact-info-footer a:hover {
  color: #b5a4a9;
}

.feedback-form-footer form {
  display: flex;
  flex-direction: column;
}

.feedback-form-footer input,
.feedback-form-footer textarea {
  background-color: #594136;
  border: transparent;
  color: #b5a4a9;
  padding: 0.8rem;
  margin-bottom: 0.8rem;
  border-radius: 0.5rem;
}

.feedback-form-footer button {
  background-color: #b2a43b;
  color: #0f152c;
  border: none;
  padding: 0.8rem 1.2rem;
  cursor: pointer;
  transition: background-color 0.3s;
  border-radius: 0.5rem;
  text-transform: uppercase;
  letter-spacing: 0.1rem;
}

.feedback-form-footer button:hover {
  background-color: #b5a4a9;
}

footer hr {
  border: 1px solid #b2a43b;
  margin: 1rem 5rem;
}

.lower-footer-section {
  text-align: center;
  font-size: 0.9rem;
  color: #b5a4a9;
}
</style>
