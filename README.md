<!-- Animated SVG: "Wave" Glow over Contribution Graph -->
<p align="center">
  <svg width="600" height="80" viewBox="0 0 600 80">
    <defs>
      <linearGradient id="fade" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#e0e7ef" />
        <stop offset="100%" stop-color="#fafbfc" />
      </linearGradient>
    </defs>
    <g>
      <rect width="600" height="80" rx="20" fill="url(#fade)" />
      <g>
        <!-- Create circles in a grid with an animated 'wave' opacity -->
        <g>
          <animateTransform attributeName="transform" type="translate" from="0 0" to="0 2" dur="1.5s" repeatCount="indefinite" />
          <!-- 10 columns x 4 rows -->
          <circle cx="30" cy="20" r="7">
            <animate attributeName="opacity" values="0.65;1;0.65" begin="0s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="70" cy="20" r="7">
            <animate attributeName="opacity" values="0.5;1;0.5" begin="0.15s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="110" cy="20" r="7">
            <animate attributeName="opacity" values="0.4;1;0.4" begin="0.3s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="150" cy="20" r="7">
            <animate attributeName="opacity" values="0.55;1;0.55" begin="0.45s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="190" cy="20" r="7">
            <animate attributeName="opacity" values="0.7;1;0.7" begin="0.6s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="230" cy="20" r="7">
            <animate attributeName="opacity" values="0.55;1;0.55" begin="0.75s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="270" cy="20" r="7">
            <animate attributeName="opacity" values="0.4;1;0.4" begin="0.9s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="310" cy="20" r="7">
            <animate attributeName="opacity" values="0.5;1;0.5" begin="1.05s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="350" cy="20" r="7">
            <animate attributeName="opacity" values="0.65;1;0.65" begin="1.2s" dur="2s" repeatCount="indefinite"/>
          </circle>
          <circle cx="390" cy="20" r="7">
            <animate attributeName="opacity" values="0.8;1;0.8" begin="1.35s" dur="2s" repeatCount="indefinite"/>
          </circle>
        </g>
        <!-- Copy and offset group for multiple rows -->
        <use href="#row" y="20"/>
        <use href="#row" y="40"/>
        <use href="#row" y="60"/>
      </g>
    </g>
  </svg>
</p>
