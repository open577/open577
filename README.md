<img width="800" height="200" alt="tech-bg" src="https://github.com/user-attachments/assets/bcc65768-bc6c-4a59-9c30-2270a4baaceb" />
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">

  <!-- 纯黑背景 -->
  <rect width="800" height="200" fill="#0a0a0a"/>

  <!-- 暗色技术支持渐变 -->
  <defs>
    <radialGradient id="glow1" cx="30%" cy="40%" r="50%">
      <stop offset="0%" stop-color="#00ff88" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#00ff88" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow2" cx="70%" cy="60%" r="50%">
      <stop offset="0%" stop-color="#0066ff" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#0066ff" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glow3" cx="50%" cy="20%" r="40%">
      <stop offset="0%" stop-color="#00ff88" stop-opacity="0.04"/>
      <stop offset="100%" stop-color="#00ff88" stop-opacity="0"/>
    </radialGradient>

    <!-- 二进制数字闪烁滤镜 -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- 发光层 -->
  <rect width="800" height="200" fill="url(#glow1)"/>
  <rect width="800" height="200" fill="url(#glow2)"/>
  <rect width="800" height="200" fill="url(#glow3)"/>

  <!-- 网格线 (暗) -->
  <g stroke="#00ff88" stroke-opacity="0.04" stroke-width="0.5">
    <line x1="0" y1="30" x2="800" y2="30"/>
    <line x1="0" y1="60" x2="800" y2="60"/>
    <line x1="0" y1="90" x2="800" y2="90"/>
    <line x1="0" y1="120" x2="800" y2="120"/>
    <line x1="0" y1="150" x2="800" y2="150"/>
    <line x1="0" y1="180" x2="800" y2="180"/>
    <line x1="100" y1="0" x2="100" y2="200"/>
    <line x1="200" y1="0" x2="200" y2="200"/>
    <line x1="300" y1="0" x2="300" y2="200"/>
    <line x1="400" y1="0" x2="400" y2="200"/>
    <line x1="500" y1="0" x2="500" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
    <line x1="700" y1="0" x2="700" y2="200"/>
  </g>

  <!-- ===== 知识/科技 符号元素 ===== -->

  <!-- 二进制数字流 (左侧) -->
  <g font-family="monospace" font-size="8" fill="#00ff88" fill-opacity="0.15" filter="url(#glow)">
    <text x="15" y="25">01001010</text>
    <text x="15" y="40">10110100</text>
    <text x="15" y="55">11010010</text>
    <text x="15" y="70">00101101</text>
    <text x="15" y="85">10010110</text>
    <text x="15" y="100">01101001</text>
    <text x="15" y="115">10110110</text>
    <text x="15" y="130">01010101</text>
    <text x="15" y="145">11001100</text>
    <text x="15" y="160">00110011</text>
    <text x="15" y="175">10101010</text>

    <!-- 右侧二进制 -->
    <text x="690" y="25">01101010</text>
    <text x="690" y="40">10011011</text>
    <text x="690" y="55">01000110</text>
    <text x="690" y="70">10101011</text>
    <text x="690" y="85">11010010</text>
    <text x="690" y="100">00110101</text>
    <text x="690" y="115">10101100</text>
    <text x="690" y="130">01011001</text>
    <text x="690" y="145">10101010</text>
    <text x="690" y="160">01010101</text>
    <text x="690" y="175">11001101</text>
  </g>

  <!-- 节点连接网络图 (科技感) -->
  <g stroke="#00ff88" stroke-opacity="0.12" stroke-width="0.8" fill="none">
    <!-- 主节点连接 -->
    <line x1="120" y1="80" x2="200" y2="130"/>
    <line x1="120" y1="80" x2="250" y2="60"/>
    <line x1="200" y1="130" x2="300" y2="100"/>
    <line x1="250" y1="60" x2="350" y2="140"/>
    <line x1="300" y1="100" x2="450" y2="70"/>
    <line x1="350" y1="140" x2="500" y2="100"/>
    <line x1="450" y1="70" x2="550" y2="130"/>
    <line x1="500" y1="100" x2="600" y2="60"/>
    <line x1="550" y1="130" x2="650" y2="90"/>
    <line x1="120" y1="80" x2="350" y2="140"/>
    <line x1="250" y1="60" x2="500" y2="100"/>
    <line x1="120" y1="80" x2="450" y2="70"/>
  </g>

  <!-- 节点圆点 -->
  <g fill="#00ff88" fill-opacity="0.2">
    <circle cx="120" cy="80" r="3"/>
    <circle cx="200" cy="130" r="2.5"/>
    <circle cx="250" cy="60" r="3.5"/>
    <circle cx="300" cy="100" r="2"/>
    <circle cx="350" cy="140" r="3"/>
    <circle cx="450" cy="70" r="2.5"/>
    <circle cx="500" cy="100" r="3.5"/>
    <circle cx="550" cy="130" r="2"/>
    <circle cx="600" cy="60" r="3"/>
    <circle cx="650" cy="90" r="2.5"/>
  </g>

  <!-- 高亮主节点 -->
  <circle cx="250" cy="60" r="6" fill="none" stroke="#00ff88" stroke-opacity="0.3" stroke-width="1">
    <animate attributeName="r" values="6;10;6" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="stroke-opacity" values="0.3;0.05;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="100" r="6" fill="none" stroke="#00ff88" stroke-opacity="0.3" stroke-width="1">
    <animate attributeName="r" values="6;9;6" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="stroke-opacity" values="0.3;0.05;0.3" dur="2.5s" repeatCount="indefinite"/>
  </circle>

  <!-- 浮动粒子 -->
  <circle cx="160" cy="50" r="1.5" fill="#00ff88" fill-opacity="0.4">
    <animate attributeName="cy" values="50;30;50" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.05;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="40" r="1" fill="#00ff88" fill-opacity="0.3">
    <animate attributeName="cy" values="40;15;40" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="580" cy="30" r="1.5" fill="#00ff88" fill-opacity="0.35">
    <animate attributeName="cy" values="30;10;30" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.35;0.05;0.35" dur="2.8s" repeatCount="indefinite"/>
  </circle>

  <!-- 中央文字 -->
  <text x="400" y="95" text-anchor="middle" font-family="monospace" font-size="22" font-weight="bold" fill="#00ff88" fill-opacity="0.7">
    &gt; Knowledge_Base.init()
  </text>
  <text x="400" y="120" text-anchor="middle" font-family="monospace" font-size="13" fill="#8b949e" fill-opacity="0.8">
    &gt; Loading... 探索 · 学习 · 创造
  </text>

  <!-- 闪烁的光标 -->
  <text x="530" y="95" font-family="monospace" font-size="22" fill="#00ff88" fill-opacity="0.5">
    <animate attributeName="opacity" values="0.5;0;0.5" dur="1s" repeatCount="indefinite"/>_
  </text>

  <!-- 底部装饰线 -->
  <line x1="300" y1="145" x2="500" y2="145" stroke="#00ff88" stroke-opacity="0.15" stroke-width="0.5"/>

  <!-- 进度条 -->
  <rect x="350" y="155" width="100" height="2" rx="1" fill="#00ff88" fill-opacity="0.08"/>
  <rect x="350" y="155" width="0" height="2" rx="1" fill="#00ff88" fill-opacity="0.3">
    <animate attributeName="width" values="0;100;0" dur="8s" repeatCount="indefinite"/>
  </rect>

  <!-- 右上角系统状态 -->
  <g font-family="monospace" font-size="7" fill="#00ff88" fill-opacity="0.12">
    <text x="680" y="8">SYS: ONLINE</text>
    <text x="680" y="18">UPTIME: 365d</text>
  </g>

</svg>
