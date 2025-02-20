<svg viewBox="0 0 400 400" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes typing {
      from { width: 0; }
      to { width: 120px; }
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }
    .code-line {
      stroke-dasharray: 50;
      stroke-dashoffset: 50;
      animation: draw 2s linear forwards infinite;
    }
    @keyframes draw {
      to {
        stroke-dashoffset: 0;
      }
    }
    .typing-text {
      animation: typing 3s steps(20) infinite;
    }
    .cursor {
      animation: blink 1s step-end infinite;
    }
    .floating {
      animation: float 3s ease-in-out infinite;
    }
    .title {
      font-family: Arial, sans-serif;
      font-size: 24px;
      fill: #D8DEE9;
    }
    .subtitle {
      font-family: Arial, sans-serif;
      font-size: 14px;
      fill: #D8DEE9;
    }
    .social-icon:hover {
      opacity: 0.8;
    }
  </style>

  <!-- Title -->
  <text x="200" y="40" text-anchor="middle" class="title">Hi 👋, I'm Nizar Afham</text>
  
  <!-- Subtitle -->
  <text x="200" y="70" text-anchor="middle" class="subtitle" width="300">
    <tspan x="200" dy="0">Computer Science student at Pertamina University with a</tspan>
    <tspan x="200" dy="20">strong interest in web and mobile app development.</tspan>
  </text>

  <!-- Background -->
  <rect x="50" y="100" width="300" height="200" fill="#2E3440" rx="10"/>
  
  <!-- Desk -->
  <rect x="50" y="250" width="300" height="20" fill="#4C566A"/>
  
  <!-- Monitor -->
  <g class="floating">
    <rect x="120" y="130" width="160" height="100" rx="5" fill="#3B4252"/>
    <rect x="125" y="135" width="150" height="90" rx="3" fill="#88C0D0"/>
    <rect x="180" y="230" width="40" height="20" fill="#4C566A"/>
    <rect x="160" y="245" width="80" height="5" fill="#4C566A"/>
    
    <!-- Code Lines -->
    <line x1="135" y1="150" x2="215" y2="150" stroke="#2E3440" stroke-width="2" class="code-line"/>
    <line x1="135" y1="170" x2="235" y2="170" stroke="#2E3440" stroke-width="2" class="code-line"/>
    <line x1="135" y1="190" x2="195" y2="190" stroke="#2E3440" stroke-width="2" class="code-line"/>
    
    <!-- Blinking Cursor -->
    <rect x="135" y="210" width="5" height="10" fill="#2E3440" class="cursor"/>
  </g>

  <!-- Coffee Cup (Corrected orientation) -->
  <g transform="translate(300, 220)">
    <path d="M0,0 L20,0 L20,-20 L0,-20 Z" fill="#D8DEE9"/>
    <path d="M20,-10 C25,-10 25,-15 20,-15" stroke="#D8DEE9" stroke-width="2" fill="none"/>
    <!-- Steam -->
    <path d="M8,-25 Q10,-35 12,-25" stroke="#D8DEE9" stroke-width="1" fill="none" class="floating"/>
    <path d="M12,-25 Q14,-35 16,-25" stroke="#D8DEE9" stroke-width="1" fill="none" class="floating"/>
  </g>

  <!-- Plant -->
  <g transform="translate(80, 220)">
    <rect x="0" y="0" width="20" height="30" fill="#4C566A"/>
    <path d="M10,-5 C0,-15 20,-15 10,-5" fill="#A3BE8C" class="floating"/>
    <path d="M10,0 C0,-10 20,-10 10,0" fill="#A3BE8C" class="floating"/>
  </g>

  <!-- Social Media Icons -->
  <h3 align="center">Connect with me:</h3>
  <p align="center">
    <a href="https://www.linkedin.com/in/nizar-afham-aflaha-80a855246?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nizar afham aflaha" height="30" width="40" /></a>
    <a href="https://instagram.com/ny.zaru" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="ny.zaru" height="30" width="40" /></a>
  </p>
</svg>




