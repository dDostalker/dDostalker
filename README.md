<!-- 赛博朋克风格CSS -->
<style>
  @keyframes neon-glow {
    0%, 100% { text-shadow: 0 0 5px #00ffff, 0 0 10px #00ffff, 0 0 15px #00ffff; }
    50% { text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff; }
  }
  
  @keyframes cyber-pulse {
    0%, 100% { box-shadow: 0 0 20px rgba(0, 255, 255, 0.5), 0 0 40px rgba(255, 0, 255, 0.3); }
    50% { box-shadow: 0 0 30px rgba(0, 255, 255, 0.8), 0 0 60px rgba(255, 0, 255, 0.5); }
  }
  
  @keyframes matrix-rain {
    0% { transform: translateY(-100%); opacity: 0; }
    50% { opacity: 1; }
    100% { transform: translateY(100vh); opacity: 0; }
  }
  
  .cyber-container {
    background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 50%, #16213e 100%);
    color: #00ffff;
    font-family: 'Courier New', monospace;
  }
  
  .neon-text {
    animation: neon-glow 2s ease-in-out infinite alternate;
    color: #00ffff;
    font-weight: bold;
  }
  
  .cyber-card {
    background: linear-gradient(135deg, rgba(0, 0, 0, 0.8) 0%, rgba(26, 26, 46, 0.9) 100%);
    border: 2px solid #00ffff;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
    animation: cyber-pulse 3s ease-in-out infinite;
  }
  
  .cyber-gradient {
    background: linear-gradient(135deg, #ff0080 0%, #00ffff 50%, #ff0080 100%);
    background-size: 200% 200%;
    animation: gradient-shift 4s ease infinite;
  }
  
  @keyframes gradient-shift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
</style>

<div class="cyber-container" align="center">
  
  <!-- 赛博朋克动态标题 -->
  <div style="margin: 30px 0;">
    <h1 class="neon-text" style="font-size: 2.5em; margin: 0; text-transform: uppercase; letter-spacing: 3px;">
      ⚡ CYBER SWORDSMAN ⚡
    </h1>
    <div style="height: 2px; background: linear-gradient(90deg, transparent, #00ffff, transparent); margin: 10px 0;"></div>
  </div>

  <!-- 动态标题 -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=20&duration=3000&pause=1000&color=00ffff&background=00000000&center=true&random=false&width=500&lines=WELCOME+TO+THE+CYBER+SWORD+GATE;FORGING+EXCELLENCE+THROUGH+CODE;MASTER+OF+DIGITAL+BLADES" alt="Typing SVG" />
  </a>

  <!-- 剑圣图片 - 赛博朋克风格 -->
  <div class="cyber-card" style="display: inline-block; padding: 10px; margin: 20px 0;">
    <img src="https://github.com/dDostalker/pictures/blob/main/jianmen.webp" alt="剑圣.webp" width="200" style="border-radius: 10px; filter: hue-rotate(180deg) brightness(1.2) contrast(1.3);"/>
  </div>

  <!-- 技术标签 - 赛博朋克风格 -->
  <div style="margin: 20px 0;">
    <img src="https://img.shields.io/badge/C++-CYBER%20CORE-00ffff?style=for-the-badge&logo=cplusplus&logoColor=black" alt="C++"/>
    <img src="https://img.shields.io/badge/PYTHON-NEURAL%20NET-ff0080?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
    <img src="https://img.shields.io/badge/REVERSE%20ENGINEERING-HACKER%20MODE-ff0080?style=for-the-badge" alt="逆向"/>
  </div>

  <!-- 访问者计数 - 赛博朋克风格 -->
  <div class="cyber-card" style="padding: 20px; margin: 20px 0; max-width: 400px;">
    <h3 class="neon-text" style="margin: 0; font-size: 1.2em;">SYSTEM ACCESS #</h3>
    <img src="https://profile-counter.glitch.me/dDostalker/count.svg" alt="Visitor Count" style="height: 50px; filter: hue-rotate(180deg) brightness(1.5);"/>
    <h3 class="neon-text" style="margin: 0; font-size: 1.2em;">CYBER WARRIOR</h3>
  </div>

</div>

---

## ⚡ CYBER CAPABILITIES ⚡

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 30px 0;">
  
  <!-- GitHub统计卡片 - 赛博朋克主题 -->
  <div class="cyber-card" style="flex: 1; min-width: 300px; padding: 15px;">
    <img src="https://github-readme-stats.vercel.app/api?username=dDostalker&theme=dark&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0a0a0a&title_color=00ffff&text_color=00ffff&icon_color=ff0080&border_color=00ffff" alt="GitHub Stats" style="width: 100%; border-radius: 10px;"/>
  </div>

  <!-- 语言统计 - 赛博朋克主题 -->
  <div class="cyber-card" style="flex: 1; min-width: 300px; padding: 15px;">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dDostalker&theme=dark&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=00ffff&text_color=00ffff&border_color=00ffff" alt="Top Languages" style="width: 100%; border-radius: 10px;"/>
  </div>

</div>

<!-- 技能图标 - 赛博朋克风格 -->
<div style="text-align: center; margin: 30px 0;">
  <h3 class="neon-text" style="margin-bottom: 20px; font-size: 1.5em;">🔧 CYBER TECH STACK 🔧</h3>
  <div class="cyber-card" style="display: inline-block; padding: 15px;">
    <img src="https://skillicons.dev/icons?i=ps,c,cpp,cs,ts,discord,twitter,vscode,git,github&perline=5" style="border-radius: 10px; filter: hue-rotate(180deg) brightness(1.2);"/>
  </div>
</div>

---

## 👨‍💻 CYBER PROFILE

<div class="cyber-card" style="display: flex; align-items: center; gap: 30px; padding: 25px; margin: 30px 0;">

  <div style="flex: 1;">
    <div style="display: flex; align-items: center; gap: 15px; margin-bottom: 15px;">
      <div style="position: relative;">
        <img src="https://github.com/dDostalker/pictures/blob/main/myself.jpg" alt="头像" style="width: 88px; height: 88px; border-radius: 50%; border: 3px solid #00ffff; filter: hue-rotate(180deg) brightness(1.1);"/>
        <div style="position: absolute; top: -5px; right: -5px; width: 20px; height: 20px; background: #ff0080; border-radius: 50%; animation: cyber-pulse 2s infinite;"></div>
      </div>
      <div>
        <h3 class="neon-text" style="margin: 0; font-size: 1.3em;">CODENAME: dDostalker / infernoid / 觌蕤</h3>
        <p style="margin: 5px 0; color: #00ffff; font-family: 'Courier New', monospace;">📍 NETWORK NODES: GitHub, 知乎, b站, csdn</p>
        <p style="margin: 5px 0; color: #00ffff; font-family: 'Courier New', monospace;">🌐 DARK WEB: Overflowr, 电报, 推特</p>
      </div>
    </div>
    
    <div class="cyber-gradient" style="padding: 15px; border-radius: 10px; text-align: center; border: 1px solid #00ffff;">
      <p style="margin: 0; color: white; font-weight: bold; font-size: 18px; text-shadow: 0 0 10px rgba(0,0,0,0.8);">MISSION OBJECTIVE:</p>
      <p style="margin: 5px 0; color: white; font-weight: bold; font-size: 20px; text-shadow: 0 0 10px rgba(0,0,0,0.8);">TECH EXCHANGE • SELF BREAKTHROUGH • PEAK EXCELLENCE</p>
    </div>
  </div>

  <div class="cyber-card" style="padding: 10px;">
    <img src="https://github.com/dDostalker/pictures/blob/main/jian.webp" alt="剑.webp" style="width: 150px; border-radius: 10px; filter: hue-rotate(180deg) brightness(1.3) contrast(1.2);"/>
  </div>

</div>

---

## 📊 CYBER ACTIVITY MATRIX

<div style="text-align: center; margin: 30px 0;">
  
  <!-- 连续贡献统计 - 赛博朋克主题 -->
  <div style="margin-bottom: 30px;">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=dDostalker&theme=dark&hide_border=true&background=0a0a0a&stroke=00ffff&ring=ff0080&fire=ff0080&currStreakNum=00ffff&sideNums=00ffff&currStreakLabel=00ffff&sideLabels=00ffff&dates=ff0080" alt="GitHub Streak" style="border-radius: 15px;"/>
  </div>

  <!-- 活动图表 - 赛博朋克主题 -->
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=dDostalker&theme=vue&hide_border=true&bg_color=0a0a0a&color=00ffff&line=ff0080&point=00ffff&area=true&area_color=ff0080&area_opacity=0.3" alt="Activity Graph" style="border-radius: 15px; max-width: 100%;"/>
    <div class="cyber-card" style="padding: 10px;">
      <img src="https://github.com/dDostalker/pictures/blob/main/jiandou.webp" alt="剑斗.webp" style="width: 200px; border-radius: 15px; filter: hue-rotate(180deg) brightness(1.2) contrast(1.3);"/>
    </div>
  </div>

</div>

---

<div class="cyber-gradient" style="text-align: center; margin-top: 50px; padding: 25px; border-radius: 15px; color: white; border: 2px solid #00ffff;">
  <p style="margin: 0; font-size: 20px; font-weight: bold; text-shadow: 0 0 10px rgba(0,0,0,0.8);">⚡ THANKS FOR ACCESSING MY CYBER PROFILE ⚡</p>
  <p style="margin: 5px 0; font-size: 16px; text-shadow: 0 0 10px rgba(0,0,0,0.8);">LET'S FORGE THE FUTURE TOGETHER IN THE DIGITAL REALM!</p>
</div> 
