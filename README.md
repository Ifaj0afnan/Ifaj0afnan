

      <svg
        width="495"
        height="165"
        viewBox="0 0 495 165"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          
    
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #777;
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    .rank-text {
      font: 800 24px 'Segoe UI', Ubuntu, Sans-Serif; fill: #777; 
      animation: scaleInAnimation 0.3s ease-in-out forwards;
    }
    
    .bold { font-weight: 700 }
    .icon {
      fill: #4c71f2;
      display: none;
    }
    
    .rank-circle-rim {
      stroke: #2f80ed;
      fill: none;
      stroke-width: 6;
      opacity: 0.2;
    }
    .rank-circle {
      stroke: #2f80ed;
      stroke-dasharray: 250;
      fill: none;
      stroke-width: 6;
      stroke-linecap: round;
      opacity: 0.8;
      transform-origin: -10px 8px;
      transform: rotate(-90deg);
      animation: rankAnimation 1s forwards ease-in-out;
    }
    
    @keyframes rankAnimation {
      from {
        stroke-dashoffset: 251.32741228718345;
      }
      to {
        stroke-dashoffset: NaN;
      }
    }
  
  
    .lang-name { font: 400 11px 'Segoe UI', Ubuntu, Sans-Serif; fill: #777 }
    

          
    /* Animations */
    @keyframes scaleInAnimation {
      from {
        transform: translate(-5px, 5px) scale(0);
      }
      to {
        transform: translate(-5px, 5px) scale(1);
      }
    }
    @keyframes fadeInAnimation {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  
        </style>

        undefined

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#E4E2E2"
          width="494"
          fill="#00000000"
          stroke-opacity="0"
        />

        

        <g
          data-testid="main-card-body"
          transform="translate(0, 25)"
        >
          
    <svg x="0" y="0" width="100%">
      <g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: NaNms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5">TypeScript:</text>
      <text 
        class="stat" 
        x="350" 
        y="12.5" 
        data-testid="TypeScript"
      >5 hrs 42 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#777"></rect>
      <rect
          height="8"
          fill="#2f80ed"
          rx="5" ry="5" x="0" y="0" 
          data-testid="lang-progress"
          width="74.39%"
      >
      </rect>
    </svg>
  
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: NaNms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5">JSON:</text>
      <text 
        class="stat" 
        x="350" 
        y="12.5" 
        data-testid="JSON"
      >38 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#777"></rect>
      <rect
          height="8"
          fill="#2f80ed"
          rx="5" ry="5" x="0" y="0" 
          data-testid="lang-progress"
          width="8.38%"
      >
      </rect>
    </svg>
  
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: NaNms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5">YAML:</text>
      <text 
        class="stat" 
        x="350" 
        y="12.5" 
        data-testid="YAML"
      >36 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#777"></rect>
      <rect
          height="8"
          fill="#2f80ed"
          rx="5" ry="5" x="0" y="0" 
          data-testid="lang-progress"
          width="7.82%"
      >
      </rect>
    </svg>
  
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: NaNms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5">HTML:</text>
      <text 
        class="stat" 
        x="350" 
        y="12.5" 
        data-testid="HTML"
      >31 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#777"></rect>
      <rect
          height="8"
          fill="#2f80ed"
          rx="5" ry="5" x="0" y="0" 
          data-testid="lang-progress"
          width="6.86%"
      >
      </rect>
    </svg>
  
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: NaNms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5">Markdown:</text>
      <text 
        class="stat" 
        x="350" 
        y="12.5" 
        data-testid="Markdown"
      >10 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#777"></rect>
      <rect
          height="8"
          fill="#2f80ed"
          rx="5" ry="5" x="0" y="0" 
          data-testid="lang-progress"
          width="2.21%"
      >
      </rect>
    </svg>
  
    </g>
  </g>
    </svg> 
  
        </g>
      </svg>
    c
