<template>
    <section class="hero">
      <video class="hero-video" autoplay muted loop playsinline>
        <source src="/videos/macVideo.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
      <div class="hero-overlay">
        <p class="hero-subtext">CREATING</p>
        <h1 class="hero-title">THE UNTHINKABLE</h1>
      </div>
    </section>
  </template>
  
  <style scoped>
  .hero {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }
  
  .hero-video {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    z-index: 0;
  }
  
  .hero-overlay {
    position: relative;
    z-index: 1;
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: rgba(0, 0, 0, 0.3);
    padding: 0 20px;
  }
  
  .hero-subtext {
    font-size: 0.9rem;
    letter-spacing: 2px;
    color: #ccc;
    margin-bottom: 10px;
    text-transform: uppercase;
  }
  
  .hero-title {
    font-size: 3.5rem;
    font-weight: 800;
    letter-spacing: 1.5px;
    color: #fff;
    text-transform: uppercase;
  }
  </style>
  