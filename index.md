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
  <a href="https://www.linkedin.com/in/lukembowers/" target="_blank" class="social-link">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="linkedin-icon">
      <path fill="currentColor" d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 
      108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 
      29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.4V304.1c0-34.3-.7-78.4-47.8-78.4-47.9 
      0-55.2 37.4-55.2 76v146.3h-92.4V148.9h88.7v40.8h1.3c12.4-23.5 
      42.6-48.3 87.7-48.3 93.7 0 111 61.7 111 141.9V448z"/>
    </svg>
  </a>
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
