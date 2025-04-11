---
layout: default
title: Secure Caravan Storage
hero_title: Secure Caravan Storage Coming Soon
hero_description: Premium storage for your caravan with 24/7 security, easy access, and competitive rates.
---

<section class="features">
  <div class="container">
    <h2>Why Choose Our Storage Facility?</h2>
    <div class="features-grid">
      {% for feature in site.data.features %}
      <div class="feature-card">
        <div class="feature-icon">{{ feature.icon }}</div>
        <h3>{{ feature.title }}</h3>
        <p>{{ feature.description }}</p>
      </div>
      {% endfor %}
    </div>
  </div>
</section>

<section class="cta-section">
  <div class="container">
    <h2>Register Your Interest</h2>
    <p>Be the first to know when we launch. Limited spaces will be available, and priority will be given to those who register early.</p>
    
    <div class="google-form-container">
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdfeYh6mf8Z_wnGE7Qhcs6iaoSkd4gp6yFEqjItY-KUkGpzbw/viewform?embedded=true" 
              width="100%" 
              height="700" 
              frameborder="0" 
              marginheight="0" 
              marginwidth="0">
        Loading…
      </iframe>
    </div>
    
    <div class="privacy-notice" id="privacy">
      {% include privacy-notice.html %}
    </div>
  </div>
</section>

<section class="location-section">
  <div class="container">
    <h2>Our Location</h2>
    <div class="location-content">
      <div class="location-info">
        <h3>Strategically Located</h3>
        <p>Our facility is situated in a prime location with excellent access to major roads, making it convenient for caravan owners throughout the region.</p>
        <p>The site features:</p>
        <ul>
          <li>Easy access from major highways</li>
          <li>Wide entrance for towing vehicles</li>
          <li>Located just outside congestion zones</li>
          <li>Close to service stations and amenities</li>
        </ul>
        <p>Exact location details will be shared with registered customers closer to our launch date.</p>
      </div>
      <div class="location-map">
        <div class="map-placeholder">
          Location Map Coming Soon
        </div>
      </div>
    </div>
  </div>
</section>