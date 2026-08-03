<svg width="800" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg" font-family="'Fira Code','Courier New',monospace">
  <defs>
    <radialGradient id="sweepGrad" cx="0%" cy="0%" r="100%">
      <stop offset="0%" stop-color="#00FF9C" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#00FF9C" stop-opacity="0"/>
    </radialGradient>
    <clipPath id="radarClip"><circle cx="140" cy="110" r="95"/></clipPath>
  </defs>

  <rect x="0" y="0" width="800" height="220" fill="#0D1117"/>

  <!-- radar housing -->
  <g clip-path="url(#radarClip)">
    <circle cx="140" cy="110" r="95" fill="#0D1117" stroke="#1F6FEB" stroke-width="1"/>
    <circle cx="140" cy="110" r="71" fill="none" stroke="#1F6FEB" stroke-width="0.75" opacity="0.5"/>
    <circle cx="140" cy="110" r="47" fill="none" stroke="#1F6FEB" stroke-width="0.75" opacity="0.5"/>
    <circle cx="140" cy="110" r="23" fill="none" stroke="#1F6FEB" stroke-width="0.75" opacity="0.5"/>
    <line x1="45" y1="110" x2="235" y2="110" stroke="#1F6FEB" stroke-width="0.5" opacity="0.4"/>
    <line x1="140" y1="15" x2="140" y2="205" stroke="#1F6FEB" stroke-width="0.5" opacity="0.4"/>

    <!-- rotating sweep -->
    <g>
      <path d="M140,110 L140,15 A95,95 0 0,1 222.5,63 Z" fill="url(#sweepGrad)">
        <animateTransform attributeName="transform" type="rotate" from="0 140 110" to="360 140 110" dur="4s" repeatCount="indefinite"/>
      </path>
    </g>

    <!-- blips: simulated "threats" flagged and neutralized -->
    <circle cx="100" cy="80" r="3.5" fill="#FF5F56">
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.35;0.4" dur="4s" begin="0.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="175" cy="140" r="3.5" fill="#FFBD2E">
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.35;0.4" dur="4s" begin="1.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="190" cy="75" r="3.5" fill="#00FF9C">
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.35;0.4" dur="4s" begin="2.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="105" cy="150" r="3.5" fill="#27C93F">
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.35;0.4" dur="4s" begin="3.5s" repeatCount="indefinite"/>
    </circle>
  </g>
  <circle cx="140" cy="110" r="96" fill="none" stroke="#00FF9C" stroke-width="1.5" opacity="0.7"/>

  <!-- readout panel -->
  <g font-size="14" fill="#8B949E">
    <text x="270" y="55" fill="#00FF9C" font-size="16" font-weight="600">LIVE THREAT SWEEP</text>
    <text x="270" y="85">grid&#160;&#160;&#160;&#160;&#160;: perimeter-01</text>
    <text x="270" y="108">scanned&#160;&#160;: 4 anomalies</text>
    <text x="270" y="131">mitigated: 4 / 4</text>
    <text x="270" y="154">status&#160;&#160;&#160;&#160;: <tspan fill="#00FF9C">secure</tspan></text>
    <text x="270" y="185" fill="#58A6FF" font-size="12">"Secure by design, tested by breach."</text>
  </g>

  <rect x="1" y="1" width="798" height="218" rx="10" fill="none" stroke="#1F6FEB" stroke-width="1.5"/>
</svg>
