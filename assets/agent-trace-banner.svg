<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#0B0E14"/>
      <stop offset="1" stop-color="#11151C"/>
    </linearGradient>
    <radialGradient id="glowAmber" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#F5A623" stop-opacity="0.9"/>
      <stop offset="1" stop-color="#F5A623" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowCyan" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#5EEAD4" stop-opacity="0.9"/>
      <stop offset="1" stop-color="#5EEAD4" stop-opacity="0"/>
    </radialGradient>
    <filter id="softBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
    <style>
      .mono { font-family: 'JetBrains Mono','Fira Code',Consolas,monospace; }
      .label { fill: #6B7280; font-size: 11px; letter-spacing: 2px; }
      .role  { fill: #C9D1D9; font-size: 13px; }
      .name  { fill: #F5A623; font-size: 34px; font-weight: 700; letter-spacing: 1px; }
      .tag   { fill: #6B7280; font-size: 13px; }
    </style>
  </defs>

  <rect width="900" height="280" fill="url(#bg)"/>

  <!-- faint grid -->
  <g stroke="#1A2029" stroke-width="1">
    <line x1="0" y1="70" x2="900" y2="70"/>
    <line x1="0" y1="140" x2="900" y2="140"/>
    <line x1="0" y1="210" x2="900" y2="210"/>
  </g>

  <!-- edges: planner -> executor -> verifier -> planner -->
  <g fill="none" stroke="#2A3140" stroke-width="1.5">
    <path d="M 130 90 L 430 60"/>
    <path d="M 430 60 L 620 170"/>
    <path d="M 620 170 L 130 90"/>
  </g>

  <!-- traveling signal pulses along edges -->
  <circle r="4" fill="#F5A623">
    <animateMotion dur="3.2s" repeatCount="indefinite"
      path="M 130 90 L 430 60 L 620 170 L 130 90 Z"/>
  </circle>
  <circle r="3" fill="#5EEAD4" opacity="0.85">
    <animateMotion dur="3.2s" begin="1.1s" repeatCount="indefinite"
      path="M 130 90 L 430 60 L 620 170 L 130 90 Z"/>
  </circle>

  <!-- PLANNER node -->
  <g transform="translate(130,90)">
    <circle r="26" fill="url(#glowAmber)" filter="url(#softBlur)"/>
    <circle r="7" fill="#F5A623">
      <animate attributeName="r" values="6;8;6" dur="2s" repeatCount="indefinite"/>
    </circle>
    <text class="mono label" x="-34" y="-38">STAGE 01</text>
    <text class="mono role" x="-34" y="-20">PLANNER</text>
  </g>

  <!-- EXECUTOR node -->
  <g transform="translate(430,60)">
    <circle r="26" fill="url(#glowAmber)" filter="url(#softBlur)"/>
    <circle r="7" fill="#F5A623">
      <animate attributeName="r" values="6;8;6" dur="2s" begin="0.6s" repeatCount="indefinite"/>
    </circle>
    <text class="mono label" x="-10" y="-38">STAGE 02</text>
    <text class="mono role" x="-10" y="-20">EXECUTOR</text>
  </g>

  <!-- VERIFIER node -->
  <g transform="translate(620,170)">
    <circle r="26" fill="url(#glowCyan)" filter="url(#softBlur)"/>
    <circle r="7" fill="#5EEAD4">
      <animate attributeName="r" values="6;8;6" dur="2s" begin="1.2s" repeatCount="indefinite"/>
    </circle>
    <text class="mono label" x="-10" y="34">STAGE 03</text>
    <text class="mono role" x="-10" y="52">VERIFIER · OK</text>
  </g>

  <!-- name block -->
  <g transform="translate(60,220)">
    <text class="mono name">
      SAURABH LOKHANDE
      <animate attributeName="opacity" values="0.75;1;0.75" dur="3.5s" repeatCount="indefinite"/>
    </text>
    <text class="mono tag" x="2" y="26">agentic-ai-engineer · LLMs · RAG · multi-agent systems</text>
  </g>

  <!-- cursor blink -->
  <rect x="700" y="242" width="10" height="18" fill="#F5A623">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>
