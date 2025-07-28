<template>
  <section class="plans-section">
    <h2 class="section-title">Flexible Weekly Plans</h2>
    <p class="section-subtitle">
      Choose the creative plan that fits your ambition. 54-week commitment applies.
    </p>

    <div class="plans-row">
      <!-- Startup Plan -->
      <div class="plan-box">
        <h3 class="plan-title">Startup</h3>
        <p class="plan-price">$350<span>/week</span></p>
        <ul class="plan-features">
          <li>1 Website</li>
          <li>Logo & Mini Brand Kit</li>
          <li>2 Monthly Design Revisions</li>
          <li>Maintenance</li>
          <li>Weekly Updates</li>
          <li>Upkeep</li>
          <li>54-Week Obligated Commitment</li>
        </ul>
        <button
          class="plan-button"
          @click="redirectToCheckout('https://buy.stripe.com/aFaeV57rpgkyaPSboD6Zy01')"
        >
          Purchase Startup Plan
        </button>
      </div>

      <!-- Growth Plan -->
      <div class="plan-box highlight">
        <h3 class="plan-title">Growth</h3>
        <p class="plan-price">$1,000<span>/week</span></p>
        <ul class="plan-features">
          <li>Everything in Startup</li>
          <li>Priority Turnarounds</li>
          <li>Unlimited Requests (1 at a time)</li>
          <li>Maintenance</li>
          <li>Weekly Updates</li>
          <li>Upkeep</li>
          <li>54-Week Obligated Commitment</li>
        </ul>
        <button
          class="plan-button"
          @click="redirectToCheckout('https://buy.stripe.com/8x28wH3b9gky4ru9gv6Zy02')"
        >
          Purchase Growth Plan
        </button>
      </div>
    </div>
  </section>
</template>

<script setup>
const redirectToCheckout = (url) => {
  window.location.href = url
}
</script>

<style scoped>
.plans-section {
  padding: 100px 20px;
  background-color: #0a0a0a;
  text-align: center;
  color: white;
}

.section-title {
  font-size: 2.4rem;
  font-weight: 700;
  margin-bottom: 12px;
}

.section-subtitle {
  color: #aaa;
  font-size: 1rem;
  margin-bottom: 50px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.plans-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
  max-width: 1100px;
  margin: 0 auto;
}

.plan-box {
  background-color: #1a1a1a;
  border: 1px solid #2e2e2e;
  border-radius: 16px;
  padding: 40px 30px;
  max-width: 320px;
  width: 100%;
  text-align: left;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.3);
}

.plan-box:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 24px rgba(0, 255, 208, 0.12);
}

.plan-box.highlight {
  border: 2px solid #00ffe1;
}

.plan-title {
  font-size: 1.6rem;
  font-weight: 600;
  color: #00ffe1;
  margin-bottom: 10px;
}

.plan-price {
  font-size: 1.4rem;
  margin-bottom: 20px;
  color: #fff;
}

.plan-price span {
  font-size: 0.9rem;
  color: #aaa;
  margin-left: 6px;
}

.plan-features {
  list-style: none;
  padding: 0;
  margin: 0 0 30px;
}

.plan-features li {
  color: #ccc;
  margin-bottom: 10px;
  font-size: 0.95rem;
}

.plan-button {
  background-color: #00ffe1;
  color: #000;
  padding: 14px 28px;
  border: none;
  border-radius: 50px;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
  width: 100%;
}

.plan-button:hover {
  background-color: #00e6cb;
}
</style>
