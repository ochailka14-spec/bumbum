<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Misi Rahasia Bum-Bum: Operasi Pilah!</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;700;800&display=swap');
  * { margin:0; padding:0; box-sizing:border-box; user-select:none; }

  body {
    font-family: 'Nunito', sans-serif;
    overflow: hidden;
    height: 100vh; width: 100vw;
    cursor: default;
  }

  /* ===== LAYERED 3D BACKGROUND ===== */
  #bg-sky {
    position: fixed; inset: 0;
    background: linear-gradient(180deg,
      #4fc3f7 0%, #81d4fa 35%,
      #b3e5fc 55%, #c8e6c9 55%,
      #81c784 70%, #66bb6a 85%, #4caf50 100%);
    z-index: 0;
  }

  /* Sun */
  #sun {
    position: fixed; top: 30px; right: 60px;
    width: 70px; height: 70px;
    background: radial-gradient(circle, #fff176, #ffee58 40%, #fdd835);
    border-radius: 50%;
    box-shadow: 0 0 0 12px rgba(255,235,59,0.2), 0 0 0 24px rgba(255,235,59,0.1), 0 0 40px 10px rgba(255,235,59,0.35);
    z-index: 1;
    animation: sunPulse 4s ease-in-out infinite;
  }
  @keyframes sunPulse {
    0%,100% { box-shadow: 0 0 0 12px rgba(255,235,59,0.2),0 0 0 24px rgba(255,235,59,0.1),0 0 40px 10px rgba(255,235,59,0.35); }
    50%      { box-shadow: 0 0 0 18px rgba(255,235,59,0.25),0 0 0 34px rgba(255,235,59,0.12),0 0 60px 15px rgba(255,235,59,0.4); }
  }

  /* Cloud layer */
  #cloud-layer { position:fixed; top:0; left:0; width:100%; height:55%; z-index:2; overflow:hidden; pointer-events:none; }
  .cloud {
    position:absolute; background:rgba(255,255,255,0.92);
    border-radius:60px; filter: drop-shadow(0 4px 8px rgba(0,0,0,0.08));
    animation: floatCloud linear infinite;
  }
  .cloud::before { content:''; position:absolute; background:inherit; border-radius:50%; width:60%; height:170%; top:-40%; left:15%; }
  .cloud::after  { content:''; position:absolute; background:inherit; border-radius:50%; width:40%; height:140%; top:-30%; right:20%; }
  @keyframes floatCloud { from{transform:translateX(-350px)} to{transform:translateX(110vw)} }

  /* Hill layers for 3D depth */
  #hill-back {
    position:fixed; bottom: 110px; left:0; right:0; height:180px;
    background: radial-gradient(ellipse 120% 100% at 50% 100%, #a5d6a7, #81c784);
    border-radius: 60% 60% 0 0 / 80% 80% 0 0;
    z-index: 3;
    filter: drop-shadow(0 -4px 12px rgba(0,0,0,0.1));
  }
  #hill-mid {
    position:fixed; bottom: 90px; left:-10%; right:-10%; height:140px;
    background: radial-gradient(ellipse 110% 100% at 50% 100%, #66bb6a, #43a047);
    border-radius: 60% 60% 0 0 / 80% 80% 0 0;
    z-index: 4;
    filter: drop-shadow(0 -3px 10px rgba(0,0,0,0.12));
  }
  #ground-flat {
    position:fixed; bottom:0; left:0; right:0; height:100px;
    background: linear-gradient(180deg, #388e3c 0%, #2e7d32 40%, #1b5e20 100%);
    z-index:5;
    box-shadow: inset 0 6px 20px rgba(0,0,0,0.2);
  }
  /* Grass stripes */
  #ground-flat::before {
    content:''; position:absolute; top:0; left:0; right:0; height:14px;
    background: repeating-linear-gradient(90deg, #4caf50 0px, #4caf50 18px, #43a047 18px, #43a047 36px);
    border-radius: 4px 4px 0 0;
  }
  /* Ground path */
  #ground-path {
    position:fixed; bottom:0; left:50%; transform:translateX(-50%);
    width:55%; height:95px;
    background: linear-gradient(180deg, #8d6e63, #6d4c41);
    z-index:6;
    clip-path: polygon(8% 0%, 92% 0%, 100% 100%, 0% 100%);
    opacity:0.4;
  }

  /* ===== TREES 3D ===== */
  .tree3d {
    position:fixed; z-index:7;
    display:flex; flex-direction:column; align-items:center;
    transform-origin:bottom center;
  }
  .tree-canopy {
    position:relative;
    width:0; height:0;
    border-left:38px solid transparent;
    border-right:38px solid transparent;
    border-bottom:90px solid #2e7d32;
    filter: drop-shadow(4px 4px 6px rgba(0,0,0,0.25));
  }
  .tree-canopy::before {
    content:''; position:absolute; top:30px; left:-28px;
    width:0; height:0;
    border-left:28px solid transparent;
    border-right:28px solid transparent;
    border-bottom:70px solid #388e3c;
  }
  .tree-canopy::after {
    content:''; position:absolute; top:58px; left:-20px;
    width:0; height:0;
    border-left:20px solid transparent;
    border-right:20px solid transparent;
    border-bottom:52px solid #43a047;
  }
  .tree-trunk3d {
    width:18px; height:32px;
    background: linear-gradient(90deg, #5d4037, #8d6e63, #5d4037);
    border-radius:3px;
    box-shadow:3px 3px 6px rgba(0,0,0,0.3);
  }

  /* ===== CHARACTER DECORATIONS ===== */
  .char-decor {
    position: fixed;
    z-index: 8;
    bottom: 92px;
    opacity: 0.92;
    filter: drop-shadow(0 8px 20px rgba(0,0,0,0.25));
    animation: charFloat 3s ease-in-out infinite;
    pointer-events: none;
  }
  @keyframes charFloat {
    0%,100% { transform: translateY(0) rotate(-1deg); }
    50%      { transform: translateY(-10px) rotate(1deg); }
  }

  /* SVG character - Girl */
  #char-girl { left: 8px; bottom: 88px; animation-delay: 0s; }
  #char-boy  { right: 8px; bottom: 88px; animation-delay: 1.5s; }

  /* ===== GAME AREA ===== */
  #gameArea {
    position:fixed; top:0; left:0; width:100%; height:100%;
    z-index: 20; overflow:hidden;
  }

  /* ===== HUD ===== */
  #hud {
    position:fixed; top:12px; left:0; right:0;
    display:flex; justify-content:space-between; align-items:center;
    padding:0 14px; z-index:100;
    pointer-events:none;
  }
  .hud-pill {
    background: linear-gradient(135deg, rgba(255,255,255,0.95), rgba(255,255,255,0.85));
    border-radius: 24px;
    padding: 7px 18px;
    font-family:'Fredoka One', cursive;
    font-size:1.3rem; color:#2d3436;
    box-shadow: 0 4px 16px rgba(0,0,0,0.15), inset 0 1px 0 rgba(255,255,255,0.9), 0 1px 0 rgba(0,0,0,0.05);
    border: 2.5px solid rgba(255,255,255,0.95);
    pointer-events:auto;
  }
  #livesBox {
    background: linear-gradient(135deg, rgba(255,255,255,0.95), rgba(255,255,255,0.85));
    border-radius: 24px; padding: 7px 14px;
    box-shadow: 0 4px 16px rgba(0,0,0,0.15), inset 0 1px 0 rgba(255,255,255,0.9);
    border: 2.5px solid rgba(255,255,255,0.95);
    display:flex; gap:4px; align-items:center;
    pointer-events:auto;
  }
  .heart { font-size:1.5rem; transition:transform 0.3s; filter:drop-shadow(0 2px 4px rgba(255,0,0,0.3)); }
  .heart.lost { filter:grayscale(1) opacity(0.3); transform:scale(0.75); }

  /* ===== BINS 3D ===== */
  #bins {
    position:fixed; bottom:0; left:0; right:0;
    display:flex; justify-content:space-around; align-items:flex-end;
    padding:0 8px 6px; z-index:60;
  }
  .bin-outer {
    display:flex; flex-direction:column; align-items:center;
    position:relative; cursor:pointer;
    filter: drop-shadow(0 8px 16px rgba(0,0,0,0.3));
    transition: filter 0.15s, transform 0.15s;
  }
  .bin-outer:hover { transform:scale(1.04); }

  /* 3D bin made with CSS */
  .bin3d {
    width:105px; height:115px; position:relative;
    transform-style: preserve-3d;
  }

  /* Front face */
  .bin-front {
    position:absolute; inset:0;
    border-radius: 10px 10px 18px 18px;
    display:flex; align-items:center; justify-content:center;
    font-size:2.8rem;
    position:relative; overflow:hidden;
  }
  /* Sheen */
  .bin-front::before {
    content:''; position:absolute; top:0; left:0; width:45%; height:100%;
    background: linear-gradient(135deg, rgba(255,255,255,0.35) 0%, rgba(255,255,255,0.05) 60%, transparent 100%);
    border-radius: inherit;
  }
  /* Ribs */
  .bin-front::after {
    content:''; position:absolute; top:14px; left:12px; right:12px;
    height:3px; border-radius:3px; background:rgba(0,0,0,0.1);
    box-shadow: 0 10px 0 rgba(0,0,0,0.08), 0 20px 0 rgba(0,0,0,0.06);
  }
  /* Right side face */
  .bin-side {
    position:absolute; top:4px; right:-16px;
    width:18px; height:108px;
    border-radius:0 8px 12px 0;
    transform: skewY(-2deg);
    background: inherit;
    filter:brightness(0.72);
  }
  /* Bottom face */
  .bin-bottom {
    position:absolute; bottom:-10px; left:4px; right:-12px;
    height:12px; border-radius:0 0 12px 12px;
    transform: skewX(-6deg);
    filter:brightness(0.6);
  }
  /* Lid */
  .bin-lid3d {
    position:absolute; top:-18px; left:-8px; right:-8px;
    height:22px; border-radius:10px 10px 0 0;
    display:flex; align-items:center; justify-content:center;
    box-shadow: 0 -2px 6px rgba(0,0,0,0.12);
  }
  .bin-lid3d::after {
    content:''; position:absolute; top:4px; left:50%; transform:translateX(-50%);
    width:22px; height:8px;
    background: rgba(0,0,0,0.12); border-radius:6px;
  }

  /* Colors */
  .bin-green  .bin-front  { background: linear-gradient(150deg, #4cdf5a 0%, #27AE60 60%, #1e8449 100%); }
  .bin-green  .bin-side   { background: #1a7a3e; }
  .bin-green  .bin-bottom { background: #145a2e; }
  .bin-green  .bin-lid3d  { background: linear-gradient(90deg, #2ECC40, #1e8449); }

  .bin-yellow .bin-front  { background: linear-gradient(150deg, #ffe033 0%, #F39C12 60%, #d68910 100%); }
  .bin-yellow .bin-side   { background: #b7770d; }
  .bin-yellow .bin-bottom { background: #9c6a09; }
  .bin-yellow .bin-lid3d  { background: linear-gradient(90deg, #F1C40F, #d4ac0d); }

  .bin-red    .bin-front  { background: linear-gradient(150deg, #ff6b60 0%, #C0392B 60%, #a93226 100%); }
  .bin-red    .bin-side   { background: #8b1a13; }
  .bin-red    .bin-bottom { background: #6e150f; }
  .bin-red    .bin-lid3d  { background: linear-gradient(90deg, #C0392B, #922b21); }

  .bin-outer.bounce  { animation: binBounce3d 0.45s ease; }
  .bin-outer.shake   { animation: binShake3d 0.45s ease; }
  @keyframes binBounce3d {
    0%   { transform: translateY(0) scale(1); }
    25%  { transform: translateY(-22px) scale(1.08) rotate(-2deg); }
    55%  { transform: translateY(0) scale(0.96) rotate(1deg); }
    75%  { transform: translateY(-8px) scale(1.02); }
    100% { transform: translateY(0) scale(1); }
  }
  @keyframes binShake3d {
    0%   { transform: translateX(0) rotate(0); }
    20%  { transform: translateX(-9px) rotate(-4deg); }
    40%  { transform: translateX(9px) rotate(4deg); }
    60%  { transform: translateX(-5px) rotate(-2deg); }
    80%  { transform: translateX(5px) rotate(2deg); }
    100% { transform: translateX(0) rotate(0); }
  }
  .bin-outer.dragover { transform:scale(1.1); filter:drop-shadow(0 10px 22px rgba(0,0,0,0.4)) brightness(1.1); }

  /* ===== TRASH ITEMS 3D ===== */
  .trash {
    position:absolute;
    width:78px; height:78px;
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    font-size:2.4rem;
    background: linear-gradient(145deg, #ffffff, #f0f0f0);
    border-radius:20px;
    box-shadow:
      0 6px 20px rgba(0,0,0,0.22),
      inset 0 1px 0 rgba(255,255,255,1),
      inset 0 -2px 0 rgba(0,0,0,0.06),
      4px 4px 0 rgba(0,0,0,0.08);
    cursor:grab;
    z-index:30;
    border: 3px solid rgba(255,255,255,0.95);
    animation: fallDown linear forwards;
    touch-action:none;
    transform-style:preserve-3d;
  }
  .trash::before {
    content:''; position:absolute; top:0; left:0; width:42%; height:42%;
    background: radial-gradient(circle at 30% 30%, rgba(255,255,255,0.8), transparent);
    border-radius:20px 0 0 0;
    pointer-events:none;
  }
  .trash:active { cursor:grabbing; }
  .trash.dragging {
    z-index:200;
    box-shadow: 0 20px 40px rgba(0,0,0,0.4), inset 0 1px 0 rgba(255,255,255,1), 4px 4px 0 rgba(0,0,0,0.1);
    transform: scale(1.15) rotate(6deg) translateZ(20px);
    animation:none !important;
  }
  .trash-label {
    font-size:0.48rem; font-family:'Nunito', sans-serif;
    font-weight:800; color:#555; text-align:center;
    line-height:1.1; padding:0 2px;
  }
  @keyframes fallDown {
    from { top:-95px; transform:rotate(-8deg); }
    25%  { transform:rotate(6deg); }
    50%  { transform:rotate(-4deg); }
    75%  { transform:rotate(5deg); }
    to   { top:100%; transform:rotate(-3deg); }
  }

  /* ===== PARTICLES ===== */
  .particle {
    position:fixed; pointer-events:none; z-index:500; font-size:1.5rem;
    animation: particleFly 0.9s ease-out forwards;
  }
  @keyframes particleFly {
    0%   { transform:translate(0,0) scale(1) rotate(0deg); opacity:1; }
    100% { transform:translate(var(--tx),var(--ty)) scale(0.2) rotate(var(--tr)); opacity:0; }
  }

  /* ===== FEEDBACK ===== */
  .feedback {
    position:fixed; z-index:600; font-family:'Fredoka One', cursive;
    font-size:2.2rem; pointer-events:none;
    animation: feedbackAnim 1s ease-out forwards;
    text-shadow: 0 3px 10px rgba(0,0,0,0.25), 0 0 20px rgba(255,255,255,0.5);
    letter-spacing:1px;
  }
  @keyframes feedbackAnim {
    0%   { transform:translateY(0) scale(0.4) rotate(-5deg); opacity:1; }
    40%  { transform:translateY(-35px) scale(1.25) rotate(3deg); opacity:1; }
    100% { transform:translateY(-90px) scale(0.9) rotate(0deg); opacity:0; }
  }

  /* ===== SCREENS ===== */
  .screen {
    position:fixed; inset:0; z-index:1000;
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    background:rgba(0,40,80,0.6); backdrop-filter:blur(8px);
    padding:20px;
  }
  .screen-card {
    background: linear-gradient(145deg, #ffffff, #f8f9fa);
    border-radius:32px; padding:32px 36px; text-align:center;
    box-shadow: 0 30px 70px rgba(0,0,0,0.35), inset 0 1px 0 rgba(255,255,255,1);
    max-width:400px; width:100%;
    border: 3px solid rgba(255,255,255,0.9);
  }
  .screen h1 { font-family:'Fredoka One',cursive; font-size:1.9rem; color:#1a237e; margin-bottom:6px; }
  .sub-title  { font-family:'Fredoka One',cursive; font-size:1.1rem; color:#e53935; margin-bottom:12px; }
  .screen p   { color:#555; font-size:0.95rem; line-height:1.6; margin-bottom:16px; }
  .legend { display:flex; flex-direction:column; gap:8px; margin-bottom:18px; text-align:left; }
  .legend-item {
    display:flex; align-items:center; gap:10px;
    padding:8px 14px; border-radius:14px; font-weight:700; font-size:0.9rem;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08), inset 0 1px 0 rgba(255,255,255,0.8);
  }
  .legend-item.green  { background:linear-gradient(135deg,#d5f5e3,#a9dfbf); color:#1a7a3a; }
  .legend-item.yellow { background:linear-gradient(135deg,#fef9e7,#fdebd0); color:#9a7d0a; }
  .legend-item.red    { background:linear-gradient(135deg,#fadbd8,#f5b7b1); color:#922b21; }
  .legend-dot { width:22px; height:22px; border-radius:50%; flex-shrink:0; box-shadow:0 2px 6px rgba(0,0,0,0.2); }

  .btn {
    background: linear-gradient(135deg, #ff7675, #d63031);
    color:white; border:none; border-radius:50px;
    padding:13px 38px; font-family:'Fredoka One',cursive;
    font-size:1.35rem; cursor:pointer;
    box-shadow: 0 6px 20px rgba(214,48,49,0.45), inset 0 1px 0 rgba(255,255,255,0.3), 0 3px 0 #b71c1c;
    transition:transform 0.15s, box-shadow 0.15s;
    letter-spacing:0.5px;
  }
  .btn:hover { transform:translateY(-3px); box-shadow:0 10px 28px rgba(214,48,49,0.5), 0 3px 0 #b71c1c; }
  .btn:active { transform:translateY(1px); box-shadow:0 3px 10px rgba(214,48,49,0.4), 0 1px 0 #b71c1c; }
  .btn.green-btn {
    background:linear-gradient(135deg,#55efc4,#00b894);
    box-shadow:0 6px 20px rgba(0,184,148,0.4), inset 0 1px 0 rgba(255,255,255,0.3), 0 3px 0 #007a63;
  }
  .btn.green-btn:hover { box-shadow:0 10px 28px rgba(0,184,148,0.5), 0 3px 0 #007a63; }

  .score-display {
    font-family:'Fredoka One',cursive; font-size:3.5rem;
    background: linear-gradient(135deg, #e17055, #d63031);
    -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;
    margin:8px 0;
  }
  .score-label { font-size:0.85rem; color:#999; font-weight:800; text-transform:uppercase; letter-spacing:2px; }

  /* Speed */
  #speedBar {
    position:fixed; top:68px; right:14px; z-index:100;
    background:rgba(255,255,255,0.88); border-radius:14px; padding:6px 12px;
    font-size:0.72rem; font-weight:800; color:#555;
    box-shadow:0 3px 10px rgba(0,0,0,0.12), inset 0 1px 0 rgba(255,255,255,0.9);
    border:2px solid rgba(255,255,255,0.95);
    display:flex; align-items:center; gap:7px;
  }
  #speedTrack { width:80px; height:9px; background:#eee; border-radius:5px; overflow:hidden; box-shadow:inset 0 1px 3px rgba(0,0,0,0.15); }
  #speedFill  { height:9px; background:linear-gradient(90deg,#00b894,#fdcb6e,#d63031); border-radius:5px; transition:width 0.5s; }

  /* Characters as CSS SVG drawings - embedded */
  .char-svg { width:110px; height:auto; }

  /* Intro char panels */
  .intro-chars {
    display:flex; justify-content:space-between; align-items:flex-end;
    margin-bottom:14px;
  }
  .intro-char { font-size:3.5rem; }
</style>
</head>
<body>

<!-- Background layers -->
<div id="bg-sky"></div>
<div id="sun"></div>
<div id="cloud-layer"></div>
<div id="hill-back"></div>
<div id="hill-mid"></div>

<!-- Characters as decorative SVG icons on sides -->
<!-- Girl character (left) -->
<div class="char-decor" id="char-girl">
  <svg width="110" height="170" viewBox="0 0 110 170" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- Body shadow -->
    <ellipse cx="55" cy="165" rx="30" ry="6" fill="rgba(0,0,0,0.15)"/>
    <!-- Shoes -->
    <ellipse cx="43" cy="158" rx="11" ry="7" fill="#212121"/>
    <ellipse cx="67" cy="158" rx="11" ry="7" fill="#212121"/>
    <!-- Socks -->
    <rect x="36" y="140" width="14" height="22" rx="5" fill="#eceff1"/>
    <rect x="60" y="140" width="14" height="22" rx="5" fill="#eceff1"/>
    <!-- Skirt -->
    <path d="M28 105 Q35 130 44 152 L66 152 Q75 130 82 105 Z" fill="#f5f0dc"/>
    <line x1="40" y1="108" x2="36" y2="150" stroke="#e0d9c0" stroke-width="1.5"/>
    <line x1="50" y1="106" x2="48" y2="152" stroke="#e0d9c0" stroke-width="1.5"/>
    <line x1="60" y1="106" x2="62" y2="152" stroke="#e0d9c0" stroke-width="1.5"/>
    <line x1="70" y1="108" x2="74" y2="150" stroke="#e0d9c0" stroke-width="1.5"/>
    <!-- Vest -->
    <path d="M34 72 L28 105 L82 105 L76 72 Z" fill="#4a7c59"/>
    <path d="M44 72 L40 105 L70 105 L66 72 Z" fill="#3d6b4a"/>
    <!-- Shirt collar -->
    <rect x="44" y="68" width="22" height="10" rx="4" fill="white"/>
    <polygon points="55,78 49,68 61,68" fill="white"/>
    <!-- Shirt sleeves -->
    <rect x="22" y="70" width="16" height="28" rx="7" fill="white"/>
    <rect x="72" y="70" width="16" height="28" rx="7" fill="white"/>
    <!-- Arm waving -->
    <ellipse cx="19" cy="68" rx="9" ry="7" fill="#f5c5a3" transform="rotate(-30 19 68)"/>
    <ellipse cx="16" cy="58" rx="7" ry="9" fill="#f5c5a3" transform="rotate(-20 16 58)"/>
    <!-- Hand fingers -->
    <circle cx="11" cy="52" r="4" fill="#f5c5a3"/>
    <circle cx="15" cy="48" r="4" fill="#f5c5a3"/>
    <circle cx="21" cy="47" r="4" fill="#f5c5a3"/>
    <!-- Hair low - pigtail -->
    <path d="M76 60 Q90 70 92 90 Q88 95 84 88 Q83 72 74 66" fill="#8B4513"/>
    <!-- Head -->
    <ellipse cx="55" cy="46" rx="28" ry="28" fill="#f5c5a3"/>
    <!-- Hair -->
    <path d="M27 40 Q28 16 55 14 Q82 16 83 40 Q80 28 55 26 Q30 28 27 40Z" fill="#8B4513"/>
    <path d="M27 38 Q24 55 28 68 Q30 60 33 50" fill="#8B4513"/>
    <path d="M83 38 Q86 55 82 68 Q80 60 77 50" fill="#8B4513"/>
    <!-- Cap -->
    <ellipse cx="55" cy="24" rx="30" ry="14" fill="#f5f0dc"/>
    <ellipse cx="55" cy="18" rx="24" ry="10" fill="#f0e8c8"/>
    <ellipse cx="55" cy="17" rx="20" ry="5" fill="#e8dc9e" opacity="0.5"/>
    <!-- Cap brim -->
    <rect x="26" y="24" width="58" height="7" rx="3" fill="#e8dc9e"/>
    <!-- Cap stripe -->
    <path d="M31 16 Q55 10 79 16" stroke="#D4AF37" stroke-width="3" fill="none"/>
    <!-- Eyes -->
    <circle cx="45" cy="48" r="7" fill="white"/>
    <circle cx="65" cy="48" r="7" fill="white"/>
    <circle cx="45" cy="49" r="5" fill="#3d1c02"/>
    <circle cx="65" cy="49" r="5" fill="#3d1c02"/>
    <circle cx="47" cy="47" r="2" fill="white"/>
    <circle cx="67" cy="47" r="2" fill="white"/>
    <!-- Blush -->
    <ellipse cx="38" cy="55" rx="7" ry="4" fill="rgba(255,150,150,0.5)"/>
    <ellipse cx="72" cy="55" rx="7" ry="4" fill="rgba(255,150,150,0.5)"/>
    <!-- Smile -->
    <path d="M46 59 Q55 67 64 59" stroke="#e57373" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    <path d="M48 60 Q55 66 62 60" fill="rgba(255,100,100,0.3)"/>
    <!-- Hair ribbon -->
    <ellipse cx="80" cy="62" rx="5" ry="3" fill="#FFD700" transform="rotate(-20 80 62)"/>
    <ellipse cx="76" cy="65" rx="5" ry="3" fill="#FFD700" transform="rotate(20 76 65)"/>
    <circle cx="78" cy="63" r="3" fill="#FFC107"/>
    <!-- Stars decoration -->
    <text x="2" y="30" font-size="14" fill="#FFD700" opacity="0.8">⭐</text>
    <text x="90" y="25" font-size="12" fill="#FF69B4" opacity="0.7">✨</text>
  </svg>
</div>

<!-- Boy character (right) -->
<div class="char-decor" id="char-boy">
  <svg width="110" height="170" viewBox="0 0 110 170" fill="none" xmlns="http://www.w3.org/2000/svg">
    <ellipse cx="55" cy="165" rx="30" ry="6" fill="rgba(0,0,0,0.15)"/>
    <!-- Shoes -->
    <ellipse cx="43" cy="158" rx="12" ry="7" fill="#212121"/>
    <ellipse cx="67" cy="158" rx="12" ry="7" fill="#212121"/>
    <!-- Socks -->
    <rect x="35" y="140" width="16" height="22" rx="5" fill="#eceff1"/>
    <rect x="59" y="140" width="16" height="22" rx="5" fill="#eceff1"/>
    <!-- Belt -->
    <rect x="30" y="104" width="52" height="8" rx="3" fill="#5d4037"/>
    <rect x="50" y="105" width="12" height="6" rx="2" fill="#9e9e9e"/>
    <!-- Shorts -->
    <path d="M30 112 L34 152 L50 152 L55 128 L60 152 L76 152 L80 112 Z" fill="#f5f0dc"/>
    <!-- Vest/jacket -->
    <path d="M30 68 L22 112 L88 112 L80 68 Z" fill="#4a7c59"/>
    <!-- Badge details on vest -->
    <rect x="36" y="76" width="16" height="10" rx="3" fill="#3d6b4a"/>
    <circle cx="58" cy="80" r="5" fill="#3d6b4a"/>
    <rect x="66" y="88" width="14" height="6" rx="2" fill="#3d6b4a"/>
    <circle cx="55" cy="94" r="3" fill="#3d6b4a"/>
    <!-- Shirt -->
    <rect x="22" y="64" width="66" height="12" rx="5" fill="white"/>
    <!-- Collar -->
    <polygon points="55,76 48,64 62,64" fill="white"/>
    <!-- Shirt sleeves -->
    <rect x="10" y="66" width="16" height="28" rx="7" fill="white"/>
    <rect x="84" y="66" width="16" height="28" rx="7" fill="white"/>
    <!-- Arm holding leaf -->
    <ellipse cx="10" cy="62" rx="9" ry="7" fill="#f5c5a3" transform="rotate(20 10 62)"/>
    <ellipse cx="7" cy="50" rx="7" ry="10" fill="#f5c5a3" transform="rotate(10 7 50)"/>
    <!-- Leaf -->
    <ellipse cx="-2" cy="38" rx="14" ry="9" fill="#8d8060" transform="rotate(-30 -2 38)"/>
    <line x1="-2" y1="38" x2="5" y2="48" stroke="#6d6040" stroke-width="1.5"/>
    <line x1="-6" y1="36" x2="-2" y2="38" stroke="#6d6040" stroke-width="1"/>
    <line x1="-3" y1="32" x2="-2" y2="38" stroke="#6d6040" stroke-width="1"/>
    <line x1="2" y1="32" x2="-2" y2="38" stroke="#6d6040" stroke-width="1"/>
    <line x1="5" y1="35" x2="-2" y2="38" stroke="#6d6040" stroke-width="1"/>
    <!-- Head -->
    <ellipse cx="55" cy="46" rx="27" ry="27" fill="#f5c5a3"/>
    <!-- Hair -->
    <path d="M28 44 Q30 18 55 16 Q80 18 82 44 Q78 26 55 24 Q32 26 28 44Z" fill="#8B4513"/>
    <path d="M30 42 Q32 36 38 34 Q32 44 32 52" fill="#8B4513"/>
    <path d="M80 42 Q78 36 72 34 Q78 44 78 52" fill="#8B4513"/>
    <!-- Short hair spikes -->
    <path d="M40 24 Q42 16 48 20" stroke="#8B4513" stroke-width="3" fill="none"/>
    <path d="M50 20 Q52 12 58 18" stroke="#8B4513" stroke-width="3" fill="none"/>
    <path d="M62 22 Q66 15 70 21" stroke="#8B4513" stroke-width="3" fill="none"/>
    <!-- Cap -->
    <ellipse cx="55" cy="24" rx="30" ry="13" fill="#f5f0dc"/>
    <ellipse cx="55" cy="18" rx="24" ry="9" fill="#f0e8c8"/>
    <rect x="26" y="24" width="58" height="7" rx="3" fill="#e8dc9e"/>
    <path d="M31 16 Q55 10 79 16" stroke="#D4AF37" stroke-width="3" fill="none"/>
    <!-- Eyes -->
    <circle cx="45" cy="48" r="7" fill="white"/>
    <circle cx="65" cy="48" r="7" fill="white"/>
    <circle cx="45" cy="49" r="5" fill="#3d1c02"/>
    <circle cx="65" cy="49" r="5" fill="#3d1c02"/>
    <circle cx="47" cy="47" r="2" fill="white"/>
    <circle cx="67" cy="47" r="2" fill="white"/>
    <!-- Blush -->
    <ellipse cx="38" cy="55" rx="7" ry="4" fill="rgba(255,150,150,0.5)"/>
    <ellipse cx="72" cy="55" rx="7" ry="4" fill="rgba(255,150,150,0.5)"/>
    <!-- Smile -->
    <path d="M46 59 Q55 67 64 59" stroke="#e57373" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    <path d="M48 60 Q55 66 62 60" fill="rgba(255,100,100,0.3)"/>
    <!-- Stars decoration -->
    <text x="90" y="30" font-size="14" fill="#FFD700" opacity="0.8">⭐</text>
    <text x="95" y="55" font-size="12" fill="#a5d6a7" opacity="0.7">🌿</text>
  </svg>
</div>

<div id="ground-flat"></div>
<div id="ground-path"></div>

<!-- HUD -->
<div id="hud">
  <div class="hud-pill">⭐ <span id="scoreVal">0</span></div>
  <div class="hud-pill" id="levelBox" style="font-size:1rem;color:#555">Level <span id="levelVal">1</span></div>
  <div id="livesBox"></div>
</div>
<div id="speedBar">
  🚀 Kecepatan
  <div id="speedTrack"><div id="speedFill" style="width:8%"></div></div>
</div>

<!-- Game Area -->
<div id="gameArea"></div>

<!-- Bins -->
<div id="bins">
  <div class="bin-outer bin-green" data-type="organik" id="binGreen">
    <div class="bin3d">
      <div class="bin-lid3d"></div>
      <div class="bin-front">🌿</div>
      <div class="bin-side"></div>
      <div class="bin-bottom"></div>
    </div>
  </div>
  <div class="bin-outer bin-yellow" data-type="anorganik" id="binYellow">
    <div class="bin3d">
      <div class="bin-lid3d"></div>
      <div class="bin-front">♻️</div>
      <div class="bin-side"></div>
      <div class="bin-bottom"></div>
    </div>
  </div>
  <div class="bin-outer bin-red" data-type="b3" id="binRed">
    <div class="bin3d">
      <div class="bin-lid3d"></div>
      <div class="bin-front">☣️</div>
      <div class="bin-side"></div>
      <div class="bin-bottom"></div>
    </div>
  </div>
</div>

<!-- Start Screen -->
<div class="screen" id="startScreen">
  <div class="screen-card">
    <div class="intro-chars">
      <span class="intro-char">👧</span>
      <div>
        <h1>Misi Rahasia Bum-Bum</h1>
        <div class="sub-title">✨ Operasi Pilah! ✨</div>
      </div>
      <span class="intro-char">👦</span>
    </div>
    <p>Geser sampah ke tong warna yang tepat sebelum jatuh ke tanah!</p>
    <div class="legend">
      <div class="legend-item green">
        <div class="legend-dot" style="background:#2ECC40"></div>
        🟢 Hijau = Organik (makanan, daun, ranting)
      </div>
      <div class="legend-item yellow">
        <div class="legend-dot" style="background:#FFDC00"></div>
        🟡 Kuning = Anorganik (plastik, botol, kertas)
      </div>
      <div class="legend-item red">
        <div class="legend-dot" style="background:#FF4136"></div>
        🔴 Merah = B3 (baterai, obat, bahan kimia)
      </div>
    </div>
    <button class="btn" onclick="startGame()">🎮 Mulai Bermain!</button>
  </div>
</div>

<!-- Game Over Screen -->
<div class="screen" id="gameOverScreen" style="display:none">
  <div class="screen-card">
    <div class="intro-chars">
      <span class="intro-char" id="goEmoji1">😢</span>
      <div>
        <h1>Permainan Selesai!</h1>
        <div class="score-label">Skor Akhirmu</div>
        <div class="score-display" id="finalScore">0</div>
      </div>
      <span class="intro-char" id="goEmoji2">😢</span>
    </div>
    <div class="score-label" id="finalMsg" style="margin-bottom:18px;color:#555;font-size:1rem;text-transform:none;letter-spacing:0"></div>
    <button class="btn green-btn" onclick="startGame()">🔄 Main Lagi!</button>
  </div>
</div>

<script>
// ============ DATA ============
const TRASH_ITEMS = {
  organik:   [
    {emoji:'🍎',label:'Apel'},{emoji:'🍌',label:'Pisang'},{emoji:'🌿',label:'Daun'},
    {emoji:'🥕',label:'Wortel'},{emoji:'🌾',label:'Ranting'},{emoji:'🍞',label:'Roti'},
    {emoji:'🥚',label:'Cangkang'},{emoji:'🌽',label:'Jagung'},{emoji:'🍃',label:'Daun Kering'},{emoji:'🥦',label:'Sayur'},
  ],
  anorganik: [
    {emoji:'🧴',label:'Botol'},{emoji:'📦',label:'Kardus'},{emoji:'🥤',label:'Gelas Plastik'},
    {emoji:'📰',label:'Koran'},{emoji:'🛍️',label:'Kantong'},{emoji:'🥫',label:'Kaleng'},
    {emoji:'📱',label:'HP Rusak'},{emoji:'🖊️',label:'Pulpen'},{emoji:'👟',label:'Sepatu'},{emoji:'🧃',label:'Kotak Jus'},
  ],
  b3: [
    {emoji:'🔋',label:'Baterai'},{emoji:'💉',label:'Jarum'},{emoji:'🧪',label:'Kimia'},
    {emoji:'🪣',label:'Cat'},{emoji:'🔌',label:'Kabel'},{emoji:'💡',label:'Lampu'},
    {emoji:'🧯',label:'Tabung'},{emoji:'🩺',label:'Obat'},{emoji:'⚗️',label:'Larutan'},
  ],
};
const BIN_COLOR  = {organik:'#2ECC40', anorganik:'#FFDC00', b3:'#FF4136'};
const CORRECT_FB = ['Hebat! 🎉','Keren! ⭐','Bagus! 🥳','Top! 🌟','Mantap! 💪','Pintar! 🏆'];
const WRONG_FB   = ['Salah! 😅','Coba Lagi! 🙈','Yah! 😬','Hati-hati! 🤔'];

// ============ STATE ============
let score=0, lives=5, gameActive=false;
let trashItems=[];
let spawnInterval, spawnRate=2800;  // slower start
let fallDuration=10000;             // much slower fall
let level=1;
let dragEl=null, dragOffX=0, dragOffY=0;

// ============ SCENE ============
function buildScene() {
  // Clouds
  const cl = document.getElementById('cloud-layer');
  cl.innerHTML='';
  for(let i=0;i<6;i++){
    const c=document.createElement('div');
    c.className='cloud';
    const w=70+Math.random()*130;
    c.style.cssText=`width:${w}px;height:${w*0.38}px;top:${5+Math.random()*45}%;left:${Math.random()*100}%;animation-duration:${22+Math.random()*25}s;animation-delay:${-Math.random()*25}s`;
    cl.appendChild(c);
  }
  // Trees (avoid bin area in center)
  const treePositions=[4,12,18,75,83,91];
  treePositions.forEach(p=>{
    const t=document.createElement('div');
    t.className='tree3d';
    t.style.cssText=`left:${p}%;bottom:${88+Math.random()*30}px;z-index:7`;
    const scale=0.7+Math.random()*0.5;
    t.style.transform=`scale(${scale})`;
    t.innerHTML='<div class="tree-canopy"></div><div class="tree-trunk3d"></div>';
    document.body.appendChild(t);
  });
  // Lives
  const lb=document.getElementById('livesBox');
  lb.innerHTML='';
  for(let i=0;i<5;i++){
    const h=document.createElement('span');
    h.className='heart';h.id='heart'+i;h.textContent='❤️';
    lb.appendChild(h);
  }
}

function clearTrees(){
  document.querySelectorAll('.tree3d').forEach(t=>t.remove());
}

function startGame(){
  document.getElementById('startScreen').style.display='none';
  document.getElementById('gameOverScreen').style.display='none';
  score=0;lives=5;level=1;
  spawnRate=2800; fallDuration=10000;
  gameActive=true;
  updateHUD();
  clearTrees();
  buildScene();
  clearAllTrash();
  if(spawnInterval) clearInterval(spawnInterval);
  spawnInterval=setInterval(spawnTrash,spawnRate);
  spawnTrash();
}

function clearAllTrash(){
  document.getElementById('gameArea').innerHTML='';
  trashItems=[];
}

// ============ SPAWN ============
function spawnTrash(){
  if(!gameActive)return;
  const types=['organik','anorganik','b3'];
  const type=types[Math.floor(Math.random()*types.length)];
  const pool=TRASH_ITEMS[type];
  const item=pool[Math.floor(Math.random()*pool.length)];

  const el=document.createElement('div');
  el.className='trash';
  el.dataset.type=type;

  const margin=90;
  const x=margin+Math.random()*(window.innerWidth-margin*2-78);
  el.style.left=x+'px';
  el.style.top='-100px';
  el.style.animationDuration=fallDuration+'ms';
  el.style.animationTimingFunction='linear';

  // Slight wobble per item
  const wobble=`@keyframes wb${Date.now()} { 0%{transform:rotate(-6deg)} 25%{transform:rotate(5deg)} 50%{transform:rotate(-4deg)} 75%{transform:rotate(4deg)} 100%{transform:rotate(-2deg)} }`;

  el.innerHTML=`<span>${item.emoji}</span><div class="trash-label">${item.label}</div>`;

  // Color dot
  const dot=document.createElement('div');
  dot.style.cssText=`position:absolute;bottom:-5px;right:-5px;width:15px;height:15px;border-radius:50%;background:${BIN_COLOR[type]};border:2.5px solid white;box-shadow:0 2px 6px rgba(0,0,0,0.25)`;
  el.appendChild(dot);

  setupDrag(el);
  document.getElementById('gameArea').appendChild(el);
  trashItems.push(el);

  el.addEventListener('animationend',()=>{
    if(!el.dataset.sorted) missedTrash(el);
  });
}

// ============ DRAG ============
function setupDrag(el){
  el.addEventListener('mousedown',dragStart);
  el.addEventListener('touchstart',dragStart,{passive:true});
}

function dragStart(e){
  if(!gameActive)return;
  dragEl=e.currentTarget;
  dragEl.classList.add('dragging');
  const rect=dragEl.getBoundingClientRect();
  const pt=e.touches?e.touches[0]:e;
  dragOffX=pt.clientX-rect.left;
  dragOffY=pt.clientY-rect.top;
  dragEl.style.position='fixed';
  dragEl.style.left=(pt.clientX-dragOffX)+'px';
  dragEl.style.top=(pt.clientY-dragOffY)+'px';
  document.addEventListener('mousemove',dragMove);
  document.addEventListener('mouseup',dragEnd);
  document.addEventListener('touchmove',dragMove,{passive:false});
  document.addEventListener('touchend',dragEnd);
}

function dragMove(e){
  if(!dragEl)return;
  if(e.cancelable)e.preventDefault();
  const pt=e.touches?e.touches[0]:e;
  dragEl.style.left=(pt.clientX-dragOffX)+'px';
  dragEl.style.top=(pt.clientY-dragOffY)+'px';
  ['binGreen','binYellow','binRed'].forEach(id=>{
    const bin=document.getElementById(id);
    if(isOver(pt.clientX,pt.clientY,bin)) bin.classList.add('dragover');
    else bin.classList.remove('dragover');
  });
}

function dragEnd(e){
  if(!dragEl)return;
  document.removeEventListener('mousemove',dragMove);
  document.removeEventListener('mouseup',dragEnd);
  document.removeEventListener('touchmove',dragMove);
  document.removeEventListener('touchend',dragEnd);
  const pt=e.changedTouches?e.changedTouches[0]:e;
  ['binGreen','binYellow','binRed'].forEach(id=>document.getElementById(id).classList.remove('dragover'));
  let dropped=false;
  const bins=[{id:'binGreen',type:'organik'},{id:'binYellow',type:'anorganik'},{id:'binRed',type:'b3'}];
  for(const b of bins){
    const binEl=document.getElementById(b.id);
    if(isOver(pt.clientX,pt.clientY,binEl)){
      processSort(dragEl,b.type,binEl,pt.clientX,pt.clientY);
      dropped=true;break;
    }
  }
  if(!dropped){
    dragEl.classList.remove('dragging');
    dragEl.style.position='absolute';
    dragEl.style.removeProperty('left');
    dragEl.style.removeProperty('top');
  }
  dragEl=null;
}

function isOver(cx,cy,el){
  const r=el.getBoundingClientRect();
  return cx>=r.left&&cx<=r.right&&cy>=r.top&&cy<=r.bottom;
}

// ============ SORT ============
function processSort(trashEl,binType,binEl,cx,cy){
  const trashType=trashEl.dataset.type;
  trashEl.dataset.sorted='1';
  removeTrash(trashEl);
  if(trashType===binType){
    score+=10+(level-1)*2; updateHUD();
    binEl.classList.add('bounce');
    setTimeout(()=>binEl.classList.remove('bounce'),500);
    showFeedback(cx,cy,CORRECT_FB[Math.floor(Math.random()*CORRECT_FB.length)],'#27AE60');
    spawnParticles(cx,cy,['⭐','✨','🎉','💫','🌟']);
    checkLevelUp();
  } else {
    loseLife();
    binEl.classList.add('shake');
    setTimeout(()=>binEl.classList.remove('shake'),500);
    showFeedback(cx,cy,WRONG_FB[Math.floor(Math.random()*WRONG_FB.length)],'#e53935');
    spawnParticles(cx,cy,['💔','❌','😬','🙈']);
  }
}

function missedTrash(el){
  if(el.dataset.sorted)return;
  el.dataset.sorted='1';
  removeTrash(el);
  loseLife();
  showFeedback(parseInt(el.style.left)+39,window.innerHeight-150,'Terlewat! 🏃','#FF8C00');
  spawnParticles(parseInt(el.style.left)+39,window.innerHeight-130,['💨','😱','🌪️']);
}

function removeTrash(el){
  const i=trashItems.indexOf(el);
  if(i>-1)trashItems.splice(i,1);
  el.remove();
}

// ============ LIVES ============
function loseLife(){
  if(!gameActive)return;
  lives--;
  const h=document.getElementById('heart'+lives);
  if(h){h.classList.add('lost');h.textContent='🖤';}
  if(lives<=0)endGame();
}

// ============ LEVEL ============
function checkLevelUp(){
  const newLevel=1+Math.floor(score/100);
  if(newLevel>level){
    level=newLevel;
    spawnRate=Math.max(900,2800-(level-1)*250);
    fallDuration=Math.max(3500,10000-(level-1)*700); // still much slower than before
    clearInterval(spawnInterval);
    spawnInterval=setInterval(spawnTrash,spawnRate);
    updateHUD();
    document.getElementById('speedFill').style.width=Math.min(100,8+(level-1)*14)+'%';
  }
}

// ============ HUD ============
function updateHUD(){
  document.getElementById('scoreVal').textContent=score;
  document.getElementById('levelVal').textContent=level;
}

// ============ FEEDBACK ============
function showFeedback(x,y,text,color){
  const f=document.createElement('div');
  f.className='feedback';f.textContent=text;
  f.style.left=(x-70)+'px';f.style.top=(y-20)+'px';f.style.color=color;
  document.body.appendChild(f);
  setTimeout(()=>f.remove(),1050);
}

function spawnParticles(x,y,emojis){
  for(let i=0;i<8;i++){
    const p=document.createElement('div');
    p.className='particle';
    p.textContent=emojis[Math.floor(Math.random()*emojis.length)];
    const angle=(Math.random()*360)*Math.PI/180;
    const dist=70+Math.random()*100;
    p.style.setProperty('--tx',Math.cos(angle)*dist+'px');
    p.style.setProperty('--ty',Math.sin(angle)*dist+'px');
    p.style.setProperty('--tr',(Math.random()*360)+'deg');
    p.style.left=x+'px';p.style.top=y+'px';
    p.style.animationDelay=(Math.random()*0.18)+'s';
    document.body.appendChild(p);
    setTimeout(()=>p.remove(),1100);
  }
}

// ============ GAME OVER ============
function endGame(){
  gameActive=false;
  clearInterval(spawnInterval);
  clearAllTrash();
  document.getElementById('finalScore').textContent=score;
  let msg='😊 Bagus sudah mencoba! Yuk main lagi!';
  let e1='😢',e2='😢';
  if(score>=300){msg='🏆 Luar biasa! Kamu Juara Pilah Sampah!';e1='🥳';e2='🎉';}
  else if(score>=150){msg='🌟 Keren! Kamu Pahlawan Lingkungan!';e1='😄';e2='⭐';}
  else if(score>=70){msg='😊 Bagus! Terus semangat belajar ya!';e1='🙂';e2='💪';}
  document.getElementById('finalMsg').textContent=msg;
  document.getElementById('goEmoji1').textContent=e1;
  document.getElementById('goEmoji2').textContent=e2;
  document.getElementById('gameOverScreen').style.display='flex';
}

// ============ BOOT ============
buildScene();
</script>
</body>
</html>
