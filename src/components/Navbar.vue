<template>
    <nav class="navbar">
      <div class="nav-container">
        <div class="logo">QUINTYN</div>
        <ul class="nav-links">
          <li><a href="#">Services</a></li>
          <li><a href="#">Plans</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    </nav>
  </template>
  
  <style scoped>
  .navbar {
    position: absolute;
    top: 0;
    width: 100%;
    z-index: 100;
    padding-top: 20px;
  }
  
  .nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
    padding: 0 2rem;
  }
  
  .logo {
    font-weight: bold;
    letter-spacing: 2px;
    font-size: 1.1rem;
    color: white;
  }
  
  .nav-links {
    display: flex;
    gap: 30px;
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .nav-links a {
    text-decoration: none;
    color: white;
    font-size: 0.95rem;
  }
  
  @media (max-width: 768px) {
    .nav-container {
      flex-direction: column;
      align-items: flex-start;
    }
  
    .nav-links {
      flex-direction: column;
      gap: 15px;
      margin-top: 10px;
    }
  }
  </style>
  