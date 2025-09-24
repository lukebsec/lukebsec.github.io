<!-- Load custom stylesheet and animation library -->
<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
<link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"/>

<!-- Particle background -->
<div id="particles-js"></div>

# Welcome

<div data-aos="fade-down">
Hi, I’m **Luke Bowers**, a Senior Security Analyst specializing in cyber defense, SOC operations, and threat detection.
</div>

## Projects

<ul>
  <li data-aos="zoom-in">🔒 <a href="#">SIEM Deployment Guide</a> – end-to-end Microsoft Sentinel rollout</li>
  <li data-aos="zoom-in">🛡️ <a href="#">Threat Hunting Playbook</a> – advanced detection engineering strategies</li>
  <li data-aos="zoom-in">⚡ <a href="#">Incident Response Case Study</a> – real-world response scenario</li>
</ul>

## About

<div data-aos="fade-up">
I help organizations strengthen their defenses against modern cyber threats.  
Let’s connect on <a href="https://linkedin.com/in/YOURUSERNAME">LinkedIn</a>.
</div>

<footer data-aos="fade-in">
  <p>© 2025 Luke Bowers — Cybersecurity Portfolio</p>
</footer>

<!-- Scripts -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>

<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
  particlesJS.load('particles-js', '{{ "/assets/particles.json" | relative_url }}', function() {
    console.log("particles.js config loaded");
  });
</script>
