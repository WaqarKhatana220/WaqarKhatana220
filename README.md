<svg viewBox="0 0 600 350" width="600" height="350" xmlns="http://www.w3.org/2000/svg">
  <!-- Background (Mac-like terminal) -->
  <rect width="100%" height="100%" rx="10" ry="10" fill="#2D2D2D"/>

  <!-- Terminal header (buttons) -->
  <circle cx="20" cy="20" r="6" fill="#FF5F56"/>
  <circle cx="40" cy="20" r="6" fill="#FFBD2E"/>
  <circle cx="60" cy="20" r="6" fill="#27C93F"/>

  <!-- Command text (static part) -->
  <text x="20" y="60" font-family="monospace" font-size="16" fill="#FFFFFF">
    khatana:~$ pip install khatana_info_
  </text>

  <!-- Fake installation progress animation (appearing and blinking one-by-one) -->
  <text x="20" y="90" font-family="monospace" font-size="16" fill="#FFFFFF" visibility="hidden">
    khatana:~$ Collecting khatana_info...
    <set attributeName="visibility" to="visible" begin="1s"/>
    <animate attributeName="opacity" values="0;1;0" dur="1s" repeatCount="2" begin="1s"/>
  </text>

  <text x="20" y="120" font-family="monospace" font-size="16" fill="#FFFFFF" visibility="hidden">
    khatana:~$ Downloading khatana_info-1.0.0.tar.gz (15 kB)
    <set attributeName="visibility" to="visible" begin="3.1s"/>
    <animate attributeName="opacity" values="0;1;0" dur="1s" repeatCount="2" begin="3.1s"/>
  </text>

  <text x="20" y="150" font-family="monospace" font-size="16" fill="#FFFFFF" visibility="hidden">
    khatana:~$ Installing collected packages: khatana_info
    <set attributeName="visibility" to="visible" begin="5.2s"/>
    <animate attributeName="opacity" values="0;1;0" dur="1s" repeatCount="2" begin="5.2s"/>
  </text>

  <text x="20" y="180" font-family="monospace" font-size="16" fill="#00FF00" visibility="hidden">
    khatana:~$ Successfully installed khatana_info-1.0.0
    <set attributeName="visibility" to="visible" begin="7.3s"/>
  </text>

  <!-- Download Resume Button -->
  <a href="https://example.com" target="_blank">
    <g visibility="hidden">
      <!-- Terminal-like button with white border -->
      <rect x="85" y="220" width="200" height="40" rx="5" ry="5" fill="#2D2D2D" stroke="#FFFFFF" stroke-width="2">
        <set attributeName="visibility" to="visible" begin="7.5s"/>
      </rect>
      <text x="115" y="245" font-family="monospace" font-size="16" fill="#FFFFFF">
        <tspan dy="0">
          <set attributeName="visibility" to="visible" begin="7.5s"/>
          Download Resume
        </tspan>
      </text>
    </g>
  </a>

  <!-- View Portfolio Button (right side) -->
  <a href="https://example.com/portfolio" target="_blank">
    <g visibility="hidden">
      <!-- Terminal-like button with white border -->
      <rect x="310" y="220" width="200" height="40" rx="5" ry="5" fill="#2D2D2D" stroke="#FFFFFF" stroke-width="2">
        <set attributeName="visibility" to="visible" begin="7.5s"/>
      </rect>
      <text x="345" y="245" font-family="monospace" font-size="16" fill="#FFFFFF">
        <tspan dy="0">
          <set attributeName="visibility" to="visible" begin="7.5s"/>
          View Portfolio
        </tspan>
      </text>
    </g>
  </a>

</svg>
