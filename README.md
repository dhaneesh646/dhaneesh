<img width="900" height="420" alt="id-card" src="https://github.com/user-attachments/assets/06b6d52f-ee2a-4160-b9c6-9b672c713c1b" />
<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="900" height="420" viewBox="0 0 900 420">
<defs>
  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#0b1324"/>
    <stop offset="100%" stop-color="#050816"/>
  </linearGradient>
  <linearGradient id="scanGrad" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="transparent"/>
    <stop offset="50%" stop-color="#00E5FF"/>
    <stop offset="100%" stop-color="transparent"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="b"/>
    <feMerge>
      <feMergeNode in="b"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>
</defs>

<rect width="900" height="420" fill="url(#bg)"/>
<rect x="30" y="30" rx="16" ry="16" width="840" height="360"
      fill="rgba(0,0,0,0)" stroke="#00E5FF" stroke-opacity="0.45"/>

<!-- HUD corners -->
<g stroke="#00E5FF" stroke-width="2" filter="url(#glow)">
 <path d="M40 60 h18 M40 60 v18"/>
 <path d="M860 60 h-18 M860 60 v18"/>
 <path d="M40 360 h18 M40 360 v-18"/>
 <path d="M860 360 h-18 M860 360 v-18"/>
</g>


<rect x="70" y="90" width="140" height="140" rx="10" fill="#0b2030" stroke="#00E5FF"/>
<!-- <text x="140" y="165" fill="#00E5FF" font-size="18" text-anchor="middle">PHOTO</text> -->

<!-- <text x="140" y="265" fill="#EAFBFF" font-size="24" text-anchor="middle">DHANEESH.M</text>
<text x="140" y="290" fill="#00E5FF" font-size="13" text-anchor="middle">SOFTWARE ENGINEER</text>
<text x="140" y="310" fill="#3D8BFF" font-size="13" text-anchor="middle">AUGRAY</text> -->

<circle cx="98" cy="338" r="5" fill="#00FFD5">
 <animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/>
</circle>
<!-- <text x="112" y="342" fill="#00FFD5" font-size="12">ONLINE</text> -->

<g font-family="Consolas, monospace">
<!-- <text x="770" y="60" fill="#3D8BFF" text-anchor="end" font-size="12">JUL 2026</text> -->

<!-- <g fill="#3D8BFF" font-size="12">
<text x="260" y="95">AGE</text>
<text x="260" y="125">EMAIL</text>
<text x="260" y="155">LOCATION</text>
<text x="260" y="185">EXPERIENCE</text>
<text x="260" y="215">EDUCATION</text>
<text x="260" y="245">SPECIALIZATION</text>
<text x="260" y="275">MISSION</text>
</g> -->

<!-- <g fill="#EAFBFF" font-size="13">
<text x="780" y="95" text-anchor="end">23 Years</text>
<text x="780" y="125" text-anchor="end">dhaneeshmofficial@gmail.com</text>
<text x="780" y="155" text-anchor="end">India</text>
<text x="780" y="185" text-anchor="end">3 Years 4 Months</text>
<text x="780" y="215" text-anchor="end">B.Sc. Software Systems · M.Sc. Information Technology</text>
<text x="780" y="245" text-anchor="end">Backend · Unity · AI Automation · CRM</text>
<text x="780" y="275" text-anchor="end">Building next-generation AI-powered CRM systems</text>
</g> -->

<!-- barcode -->
<g transform="translate(300,320)">
<rect x="0" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="4" y="0" width="1" height="24" fill="#00E5FF"/>
<rect x="7" y="0" width="3" height="24" fill="#00E5FF"/>
<rect x="12" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="16" y="0" width="4" height="24" fill="#00E5FF"/>
<rect x="22" y="0" width="1" height="24" fill="#00E5FF"/>
<rect x="25" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="29" y="0" width="5" height="24" fill="#00E5FF"/>
<rect x="36" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="40" y="0" width="3" height="24" fill="#00E5FF"/>
<rect x="45" y="0" width="1" height="24" fill="#00E5FF"/>
<rect x="48" y="0" width="4" height="24" fill="#00E5FF"/>
<rect x="54" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="58" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="62" y="0" width="5" height="24" fill="#00E5FF"/>
<rect x="69" y="0" width="1" height="24" fill="#00E5FF"/>
<rect x="72" y="0" width="3" height="24" fill="#00E5FF"/>
<rect x="77" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="81" y="0" width="4" height="24" fill="#00E5FF"/>
<rect x="87" y="0" width="1" height="24" fill="#00E5FF"/>
<rect x="90" y="0" width="2" height="24" fill="#00E5FF"/>
<rect x="94" y="0" width="3" height="24" fill="#00E5FF"/>
<rect x="99" y="0" width="5" height="24" fill="#00E5FF"/>
<!-- <text x="120" y="42" fill="#00E5FF" font-size="11">ID : 17042003-DN</text> -->
</g>
</g>

<!-- scan line -->
<rect x="35" y="0" width="830" height="3" fill="#00E5FF" filter="url(#glow)">
  <animate attributeName="y" values="25;390;25" dur="3.5s" repeatCount="indefinite"/>
</rect>

<!-- hologram sheen -->
<rect x="-300" y="30" width="180" height="360" fill="white" opacity="0.08" transform="skewX(-20)">
 <animate attributeName="x" values="-300;980" dur="6s" repeatCount="indefinite"/>
</rect>
</svg>
