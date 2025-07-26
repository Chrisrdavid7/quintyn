<template>
    <footer class="footer">
      <div class="footer-content">
        <!-- Left Section -->
        <div class="footer-left">
          <img src="/images/Qlogo.png" alt="Quintyn Logo" class="footer-logo" />
          <p class="footer-tagline">Tech-driven creative for visionaries.</p>
          <p class="copyright">© 2025 Quintyn Holdings LLC</p>
        </div>
  
        <!-- Right Section -->
        <div class="footer-right">
          <h4 class="footer-heading">Connect</h4>
          <div class="social-icons">
            <a href="mailto:hello@quintynholdings.com" aria-label="Email">
              <i class="fas fa-envelope"></i>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background: #0a0a0a;
    padding: 60px 20px;
    color: #ccc;
    font-size: 0.95rem;
  }
  
  .footer-content {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 40px;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .footer-left,
  .footer-right {
    flex: 1;
    min-width: 260px;
  }
  
  .footer-logo {
    max-width: 70px;
    margin-bottom: 16px;
  }
  
  .footer-tagline {
    margin-bottom: 8px;
    color: #eee;
    font-size: 1rem;
    line-height: 1.4;
  }
  
  .footer-heading {
    margin-bottom: 12px;
    color: #fff;
    font-size: 1.1rem;
  }
  
  .social-icons a {
    margin-right: 18px;
    color: #00ffe1;
    font-size: 1.25rem;
    transition: color 0.3s ease;
  }
  
  .social-icons a:hover {
    color: #00d4c0;
  }
  
  @media (max-width: 640px) {
    .footer-content {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  
    .footer-left,
    .footer-right {
      margin-bottom: 30px;
    }
  
    .social-icons a {
      margin-right: 12px;
    }
  }
  </style>
  