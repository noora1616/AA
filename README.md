<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AQUA-AI | AI-Powered Dehydration & Heat Stress Prevention</title>
  <style>
    /* Global Styles */
    :root {
      --primary: #0066cc;  /* Trust blue */
      --secondary: #ff3333; /* Alert red */
      --dark: #333;
      --light: #f9f9f9;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      color: var(--dark);
      line-height: 1.6;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
    }
    .btn {
      display: inline-block;
      padding: 12px 30px;
      background: var(--primary);
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: all 0.3s;
    }
    .btn:hover {
      background: #004d99;
    }
    .btn-secondary {
      background: var(--secondary);
    }
    .btn-secondary:hover {
      background: #cc0000;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1509316785289-025f5b846b35?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 100px 0;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto 30px;
    }
    .hero-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    /* Problem Section */
    .problem {
      padding: 80px 0;
      background: var(--light);
      text-align: center;
    }
    .problem h2 {
      font-size: 2.5rem;
      color: var(--primary);
      margin-bottom: 40px;
    }
    .problem-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 30px;
      margin-top: 40px;
    }
    .problem-card {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }
    .problem-card h3 {
      color: var(--secondary);
      font-size: 1.5rem;
    }

    /* How It Works */
    .how-it-works {
      padding: 80px 0;
      text-align: center;
    }
    .how-it-works h2 {
      font-size: 2.5rem;
      color: var(--primary);
    }
    .steps {
      display: flex;
      justify-content: space-around;
      margin-top: 50px;
      flex-wrap: wrap;
    }
    .step {
      width: 30%;
      min-width: 250px;
      margin-bottom: 30px;
    }
    .step-icon {
      font-size: 3rem;
      color: var(--primary);
      margin-bottom: 20px;
    }

    /* CTA Section */
    .cta {
      background: var(--primary);
      color: white;
      text-align: center;
      padding: 80px 0;
    }
    .cta h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    .cta p {
      max-width: 700px;
      margin: 0 auto 30px;
      font-size: 1.2rem;
    }

    /* Footer */
    footer {
      background: var(--dark);
      color: white;
      padding: 40px 0;
      text-align: center;
    }
    .footer-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 20px;
    }
    .footer-links a {
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Prevent Dehydration & Heat Stroke with AI-Powered Surveillance</h1>
      <p>AQUA-AI detects early signs of heat stress and dehydration using thermal imaging, motion sensing, and facial analysis—saving lives at Hajj, construction sites, and major events.</p>
      <div class="hero-buttons">
        <a href="#contact" class="btn">Request a Demo</a>
        <a href="#contact" class="btn btn-secondary">Partner with Us</a>
      </div>
    </div>
  </section>

  <!-- Problem Section -->
  <section class="problem">
    <div class="container">
      <h2>The Hidden Killer: Dehydration & Heat Stress</h2>
      <div class="problem-grid">
        <div class="problem-card">
          <h3>☀️ Extreme Heat Kills</h3>
          <p>51.8°C recorded in Mecca during Hajj 2024. Over 1,301 pilgrims died from heat-related illnesses.</p>
        </div>
        <div class="problem-card">
          <h3>💧 Dehydration is Silent</h3>
          <p>Victims often collapse without warning. Thirst means you're already dehydrated.</p>
        </div>
        <div class="problem-card">
          <h3>🚑 Current Solutions Fail</h3>
          <p>Wearables are expensive and impractical for mass events. Manual monitoring is too slow.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works -->
  <section class="how-it-works">
    <div class="container">
      <h2>AI That Saves Lives in Real Time</h2>
      <div class="steps">
        <div class="step">
          <div class="step-icon">🌡️</div>
          <h3>Thermal Sensors</h3>
          <p>Detects body temperature >40°C (heat stroke threshold).</p>
        </div>
        <div class="step">
          <div class="step-icon">🚶</div>
          <h3>Motion Analysis</h3>
          <p>Flags unsteady gait (ataxia) and lethargic movement.</p>
        </div>
        <div class="step">
          <div class="step-icon">👁️</div>
          <h3>Facial Recognition</h3>
          <p>Identifies sunken eyes, reduced blinking, and facial cues of dehydration.</p>
        </div>
      </div>
      <p style="margin-top: 50px; font-weight: bold;">
        Seamlessly integrated with Saudi Arabia’s <strong>Nusuk Hajj system</strong> for instant pilgrim ID and medical history access.
      </p>
    </div>
  </section>

  <!-- Use Cases -->
  <section class="problem" style="background: white;">
    <div class="container">
      <h2 style="color: var(--primary);">Where AQUA-AI Makes an Impact</h2>
      <div class="problem-grid">
        <div class="problem-card">
          <h3>🕋 Hajj & Umrah</h3>
          <p>Prevent tragedies like 2024’s 1,301 heat-related deaths.</p>
        </div>
        <div class="problem-card">
          <h3>🏗️ Construction Sites</h3>
          <p>Protect workers in 50°C+ environments.</p>
        </div>
        <div class="problem-card">
          <h3>⚽ FIFA 2034 & Mega-Events</h3>
          <p>Ensure crowd safety with real-time monitoring.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="cta" id="contact">
    <div class="container">
      <h2>Join the Movement to Save Lives</h2>
      <p>Deploy AQUA-AI for Hajj 2025 or your next event. Contact us for a demo or partnership opportunities.</p>
      <a href="#contact" class="btn" style="background: white; color: var(--primary);">Get a Pilot Deployment</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <div class="footer-links">
        <a href="#">FAQ</a>
        <a href="#">Privacy Policy</a>
        <a href="#">SDG Impact Report</a>
      </div>
      <p>Contact: info@aqua-ai.com | +966 XXX XXX XXXX</p>
      <p>© 2025 AQUA-AI. Aligns with Saudi Vision 2030.</p>
    </div>
  </footer>
</body>
</html>
