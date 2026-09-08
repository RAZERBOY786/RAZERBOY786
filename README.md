<svg viewBox="0 0 1200 200" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="bg2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0f2027"/>
      <stop offset="50%" stop-color="#142b2e"/>
      <stop offset="100%" stop-color="#0f2027"/>
    </linearGradient>
  </defs>

  <!-- Background -->

<rect
 width="1200"
 height="200"
 fill="url(#bg2)"
 rx="14"
/>

  <!-- Scanlines -->

<g
stroke="#20E680"
stroke-width="1"
opacity="0.05"

>

```
<line x1="0" y1="20" x2="1200" y2="20"/>
```

```
<line x1="0" y1="60" x2="1200" y2="60"/>
<line x1="0" y1="100" x2="1200" y2="100"/>
<line x1="0" y1="140" x2="1200" y2="140"/>
<line x1="0" y1="180" x2="1200" y2="180"/>
```

  </g>

  <!-- Bullet Tracers -->

<g
stroke="#20E680"
stroke-width="2"
opacity="0.5"

>

```
<line x1="-40" y1="50" x2="20" y2="50">
  <animateMotion
    path="M0,0 L1300,0"
    dur="1.1s"
    repeatCount="indefinite"
  />
</line>

<line x1="-40" y1="150" x2="20" y2="150">
  <animateMotion
    path="M0,0 L1300,0"
    dur="1.5s"
    begin="0.4s"
    repeatCount="indefinite"
  />
</line>
```

  </g>

  <!-- Scanning Crosshair -->

<g
stroke="#20E680"
stroke-width="1.6"
fill="none"

>

```
<g>

  <circle
    cx="0"
    cy="0"
    r="14"
  />

  <line x1="-22" y1="0" x2="-10" y2="0"/>
  <line x1="10" y1="0" x2="22" y2="0"/>

  <line x1="0" y1="-22" x2="0" y2="-10"/>
  <line x1="0" y1="10" x2="0" y2="22"/>

  <animateMotion
    path="M550,60 L720,30 L800,90 L600,110 L550,60"
    dur="6s"
    repeatCount="indefinite"
  />

</g>
```

  </g>

  <!-- Hit Marker -->

<g
stroke="#ff4d4d"
stroke-width="2"
opacity="0"

>

```
<line
  x1="590"
  y1="55"
  x2="610"
  y2="75"
/>

<line
  x1="610"
  y1="55"
  x2="590"
  y2="75"
/>

<animate
  attributeName="opacity"
  values="0;0;1;0;0;0"
  keyTimes="0;0.15;0.18;0.3;0.5;1"
  dur="6s"
  repeatCount="indefinite"
/>
```

  </g>

  <!-- Controller -->

  <g transform="translate(60,90)">

```
<path
  d="M0 20
     Q0 -10 30 -10
     L90 -10
     Q120 -10 120 20
     Q120 45 100 45
     Q90 45 85 30
     L35 30
     Q30 45 20 45
     Q0 45 0 20 Z"
  fill="#1a3336"
  stroke="#20E680"
  stroke-width="1.4"
/>

<!-- Joystick -->
<circle
  cx="30"
  cy="12"
  r="9"
  fill="#0f2027"
  stroke="#20E680"
  stroke-width="1"
/>

<circle
  cx="30"
  cy="12"
  r="3"
  fill="#20E680"
>
  <animateTransform
    attributeName="transform"
    type="translate"
    values="0,0;2,1;-2,-1;0,0"
    dur="1.6s"
    repeatCount="indefinite"
  />
</circle>

<!-- Controller Buttons -->
<g fill="#20E680">

  <circle
    cx="95"
    cy="4"
    r="4"
    opacity="0.3"
  >
    <animate
      attributeName="opacity"
      values="0.3;1;0.3"
      dur="1.6s"
      begin="0s"
      repeatCount="indefinite"
    />
  </circle>

  <circle
    cx="107"
    cy="16"
    r="4"
    opacity="0.3"
  >
    <animate
      attributeName="opacity"
      values="0.3;1;0.3"
      dur="1.6s"
      begin="0.4s"
      repeatCount="indefinite"
    />
  </circle>

  <circle
    cx="95"
    cy="28"
    r="4"
    opacity="0.3"
  >
    <animate
      attributeName="opacity"
      values="0.3;1;0.3"
      dur="1.6s"
      begin="0.8s"
      repeatCount="indefinite"
    />
  </circle>

  <circle
    cx="83"
    cy="16"
    r="4"
    opacity="0.3"
  >
    <animate
      attributeName="opacity"
      values="0.3;1;0.3"
      dur="1.6s"
      begin="1.2s"
      repeatCount="indefinite"
    />
  </circle>

</g>
```

  </g>

  <!-- GG WP -->

<text
x="55"
y="160"
fill="#20E680"
font-family="monospace"
font-size="11"
opacity="0.75"

>

```
GG WP
```

  </text>

  <!-- FPS Game Badges -->

<g
font-family="monospace"
font-size="16"
font-weight="bold"
text-anchor="middle"

>

```
<!-- PUBG -->
<g transform="translate(900,60)">

  <rect
    x="-55"
    y="-20"
    width="110"
    height="34"
    rx="8"
    fill="#1a3336"
    stroke="#20E680"
    stroke-width="1.2"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="0s"
      repeatCount="indefinite"
    />
  </rect>

  <text
    y="2"
    fill="#20E680"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="0s"
      repeatCount="indefinite"
    />
    PUBG
  </text>

</g>

<!-- VALORANT -->
<g transform="translate(900,60)">

  <rect
    x="-55"
    y="-20"
    width="110"
    height="34"
    rx="8"
    fill="#1a3336"
    stroke="#20E680"
    stroke-width="1.2"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="0.5s"
      repeatCount="indefinite"
    />
  </rect>

  <text
    y="2"
    fill="#20E680"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="0.5s"
      repeatCount="indefinite"
    />
    VALORANT
  </text>

</g>

<!-- CS:GO -->
<g transform="translate(900,60)">

  <rect
    x="-55"
    y="-20"
    width="110"
    height="34"
    rx="8"
    fill="#1a3336"
    stroke="#20E680"
    stroke-width="1.2"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="1s"
      repeatCount="indefinite"
    />
  </rect>

  <text
    y="2"
    fill="#20E680"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="1s"
      repeatCount="indefinite"
    />
    CS:GO
  </text>

</g>

<!-- COD -->
<g transform="translate(900,60)">

  <rect
    x="-55"
    y="-20"
    width="110"
    height="34"
    rx="8"
    fill="#1a3336"
    stroke="#20E680"
    stroke-width="1.2"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="1.5s"
      repeatCount="indefinite"
    />
  </rect>

  <text
    y="2"
    fill="#20E680"
    opacity="0"
  >
    <animate
      attributeName="opacity"
      values="0;1;0"
      keyTimes="0;0.5;1"
      dur="2s"
      begin="1.5s"
      repeatCount="indefinite"
    />
    COD
  </text>

</g>
```

  </g>

  <!-- FPS Lobby -->

<text
x="845"
y="115"
fill="#20E680"
font-family="monospace"
font-size="11"
opacity="0.75"

>

```
FPS LOBBY
```

  </text>

  <!-- KDA -->

<g
font-family="monospace"
font-size="12"
fill="#20E680"
opacity="0.6"

>

```
<text x="1010" y="150">
  K/D/A: 24/6/11

  <animate
    attributeName="opacity"
    values="0.3;0.8;0.3"
    dur="2.4s"
    repeatCount="indefinite"
  />

</text>
```

  </g>

</svg>
