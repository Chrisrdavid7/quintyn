<template>
    <section class="services-section">
      <h2 class="section-title">What We Do</h2>
      <div class="services-grid">
        <div class="service-card">
          <h3>Web Design</h3>
          <p>
            Custom, responsive websites that capture your brand and drive conversions.
          </p>
        </div>
        <div class="service-card">
          <h3>Branding</h3>
          <p>
            Logo design, brand identity systems, and storytelling visuals that last.
          </p>
        </div>
        <div class="service-card">
          <h3>Creative Support</h3>
          <p>
            Ongoing design requests, revisions, and consulting — all under one flat monthly rate.
          </p>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .services-section {
    background-color: #0a0a0a;
    padding: 80px 20px;
    text-align: center;
    color: #fff;
  }
  
  /* Title */
  .section-title {
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 40px;
  }
  
  /* Grid Layout */
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  /* Service Card Styling */
  .service-card {
    background-color: #141414;
    border-radius: 16px;
    padding: 30px 24px;
    text-align: left;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .service-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 10px 20px rgba(0, 255, 180, 0.15);
  }
  
  .service-card h3 {
    color: #00ffd1;
    margin-bottom: 10px;
    font-size: 1.2rem;
  }
  
  .service-card p {
    color: #bbb;
    font-size: 0.95rem;
    line-height: 1.6;
  }
  </style>
  