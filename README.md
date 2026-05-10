cat > /mnt/user-data/outputs/profile-card.svg << 'SVGEOF'
<svg width="680" viewBox="0 0 680 1616" xmlns="http://www.w3.org/2000/svg" font-family="'JetBrains Mono','Courier New',monospace">
<defs>
  <style>
    .blink{animation:blink 1s step-end infinite}
    @keyframes blink{50%{opacity:0}}
    .b1{animation:g1 1.2s ease-out both}
    .b2{animation:g2 1.2s .1s ease-out both}
    .b3{animation:g3 1.2s .2s ease-out both}
    .b4{animation:g4 1.2s .3s ease-out both}
    .b5{animation:g5 1.2s .4s ease-out both}
    .b6{animation:g6 1.2s .5s ease-out both}
    @keyframes g1{from{width:0}to{width:364px}}
    @keyframes g2{from{width:0}to{width:352px}}
    @keyframes g3{from{width:0}to{width:340px}}
    @keyframes g4{from{width:0}to{width:320px}}
    @keyframes g5{from{width:0}to{width:296px}}
    @keyframes g6{from{width:0}to{width:272px}}
  </style>
  <linearGradient id="gv" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#00ff88"/>
    <stop offset="100%" stop-color="#a855f7"/>
  </linearGradient>
  <linearGradient id="vv" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#7c3aed"/>
    <stop offset="100%" stop-color="#a855f7"/>
  </linearGradient>
</defs>

<!-- BG -->
<rect width="680" height="1616" rx="12" fill="#060608"/>
<rect width="680" height="1616" rx="12" fill="none" stroke="#2d1b4e" stroke-width="1"/>

<!-- TITLEBAR -->
<rect width="680" height="42" rx="12" fill="#0a0a14"/>
<rect y="24" width="680" height="18" fill="#0a0a14"/>
<rect y="41" width="680" height="1" fill="#1a1a2e"/>
<circle cx="22" cy="21" r="6" fill="#ff5f56"/>
<circle cx="42" cy="21" r="6" fill="#ffbd2e"/>
<circle cx="62" cy="21" r="6" fill="#27c93f"/>
<text x="340" y="26" text-anchor="middle" fill="#4a5568" font-size="11">noxustic@bot-engineers ~ zsh</text>

<!-- BOOT LINES y=52 -->
<text x="32" y="74" fill="#27c93f" font-size="11">[  OK  ]</text><text x="102" y="74" fill="#4a5568" font-size="11">Starting system profile...</text>
<text x="32" y="92" fill="#27c93f" font-size="11">[  OK  ]</text><text x="102" y="92" fill="#4a5568" font-size="11">Loading embedded systems driver...</text>
<text x="32" y="110" fill="#a855f7" font-size="11">[ WARN ]</text><text x="102" y="110" fill="#4a5568" font-size="11">Coffee levels: critically low</text>
<text x="32" y="128" fill="#27c93f" font-size="11">[  OK  ]</text><text x="102" y="128" fill="#4a5568" font-size="11">Mounting /dev/robot ... done</text>

<!-- PROMPT 1 y=134 -->
<text x="32" y="154" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="154" fill="#00ff88" font-size="13">cat ./profile.json</text>

<!-- ASCII banner y=154 -->
<text x="30" y="172" fill="#00ff88" font-size="9.4">&#x2588;&#x2588;&#x2588;&#x2557;   &#x2588;&#x2588;&#x2557; &#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557; &#x2588;&#x2588;&#x2557;  &#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2557;   &#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2557; &#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;</text>
<text x="30" y="185" fill="#00ff88" font-size="9.4">&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;  &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2554;&#x2550;&#x2550;&#x2550;&#x2588;&#x2588;&#x2557;&#x255A;&#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2554;&#x255D;&#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2554;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D;&#x255A;&#x2550;&#x2550;&#x2588;&#x2588;&#x2554;&#x2550;&#x2550;&#x255D;&#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2554;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D;</text>
<text x="30" y="198" fill="#00ff88" font-size="9.4">&#x2588;&#x2588;&#x2554;&#x2588;&#x2588;&#x2557; &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551; &#x255A;&#x2588;&#x2588;&#x2588;&#x2554;&#x255D; &#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;      &#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2551;</text>
<text x="30" y="211" fill="#00ff88" font-size="9.4">&#x2588;&#x2588;&#x2551;&#x255A;&#x2588;&#x2588;&#x2557;&#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551; &#x2588;&#x2588;&#x2554;&#x2588;&#x2588;&#x2557; &#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2554;&#x2550;&#x2550;&#x255D;      &#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x2588;&#x2588;&#x2551;</text>
<text x="30" y="224" fill="#00ff88" font-size="9.4">&#x2588;&#x2588;&#x2551; &#x255A;&#x2588;&#x2588;&#x2588;&#x2588;&#x2551;&#x255A;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2554;&#x255D;&#x2588;&#x2588;&#x2554;&#x255D; &#x2588;&#x2588;&#x2557;&#x255A;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2554;&#x255D;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;   &#x2588;&#x2588;&#x2551;   &#x2588;&#x2588;&#x2551;&#x255A;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2557;</text>
<text x="30" y="237" fill="#00ff88" font-size="9.4">&#x255A;&#x2550;&#x255D;  &#x255A;&#x2550;&#x2550;&#x2550;&#x255D; &#x255A;&#x2550;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D; &#x255A;&#x2550;&#x255D;  &#x255A;&#x2550;&#x255D; &#x255A;&#x2550;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D; &#x255A;&#x2550;&#x2550;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D;   &#x255A;&#x2550;&#x255D;   &#x255A;&#x2550;&#x255D; &#x255A;&#x2550;&#x2550;&#x2550;&#x2550;&#x2550;&#x255D;</text>
<text x="32" y="256" fill="#4a5568" font-size="11" font-style="italic">// "Building robots that bridge the gap between imagination and reality."</text>

<!-- PROMPT 2 whoami y=270 -->
<text x="32" y="290" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="290" fill="#00ff88" font-size="13">whoami --verbose</text>
<rect x="32" y="300" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="316" fill="#a855f7" font-size="10" letter-spacing="2">// IDENTITY</text>

<text x="52" y="338" fill="#4a5568" font-size="12">alias         :</text><text x="185" y="338" fill="#a855f7" font-size="12">NOXUSTIC</text>
<text x="52" y="356" fill="#4a5568" font-size="12">real_name     :</text><text x="185" y="356" fill="#c8ffd4" font-size="12">Saadat S. Rahman</text>
<text x="52" y="374" fill="#4a5568" font-size="12">role          :</text><text x="185" y="374" fill="#00ff88" font-size="12">CTO @ BOT Engineers</text>
<text x="52" y="392" fill="#4a5568" font-size="12">location      :</text><text x="185" y="392" fill="#c8ffd4" font-size="12">Narayanganj, BD</text>
<text x="52" y="410" fill="#4a5568" font-size="12">pronouns      :</text><text x="185" y="410" fill="#c8ffd4" font-size="12">he/him</text>
<text x="52" y="428" fill="#4a5568" font-size="12">fun_fact      :</text><text x="185" y="428" fill="#a855f7" font-size="12">"I build robots for fun"</text>

<!-- PROMPT 3 lspci y=436 -->
<text x="32" y="456" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="456" fill="#00ff88" font-size="13">lspci | grep -i "skill"</text>

<!-- EMBEDDED -->
<rect x="32" y="466" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="480" fill="#a855f7" font-size="10" letter-spacing="2">// EMBEDDED + ROBOTICS</text>
<rect x="32" y="488" width="72" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="68" y="502" text-anchor="middle" fill="#a855f7" font-size="10">Arduino</text>
<rect x="112" y="488" width="40" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="132" y="502" text-anchor="middle" fill="#a855f7" font-size="10">ROS</text>
<rect x="160" y="488" width="118" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="219" y="502" text-anchor="middle" fill="#a855f7" font-size="10">Autodesk Fusion</text>
<rect x="286" y="488" width="88" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="330" y="502" text-anchor="middle" fill="#a855f7" font-size="10">SolidWorks</text>
<rect x="382" y="488" width="64" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="414" y="502" text-anchor="middle" fill="#a855f7" font-size="10">OpenCV</text>
<rect x="454" y="488" width="60" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="484" y="502" text-anchor="middle" fill="#a855f7" font-size="10">MATLAB</text>
<rect x="522" y="488" width="84" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="564" y="502" text-anchor="middle" fill="#a855f7" font-size="10">TensorFlow</text>
<rect x="32" y="516" width="48" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="56" y="530" text-anchor="middle" fill="#a855f7" font-size="10">Linux</text>
<rect x="88" y="516" width="46" height="20" rx="2" fill="#0e0818" stroke="#3b1f6a" stroke-width="1"/><text x="111" y="530" text-anchor="middle" fill="#a855f7" font-size="10">Bash</text>

<!-- LANGUAGES -->
<rect x="32" y="546" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="560" fill="#a855f7" font-size="10" letter-spacing="2">// LANGUAGES</text>
<rect x="32" y="568" width="24" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="44" y="582" text-anchor="middle" fill="#00ff88" font-size="10">C</text>
<rect x="64" y="568" width="36" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="82" y="582" text-anchor="middle" fill="#00ff88" font-size="10">C++</text>
<rect x="108" y="568" width="60" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="138" y="582" text-anchor="middle" fill="#00ff88" font-size="10">Python</text>
<rect x="176" y="568" width="92" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="222" y="582" text-anchor="middle" fill="#00ff88" font-size="10">JavaScript</text>
<rect x="276" y="568" width="46" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="299" y="582" text-anchor="middle" fill="#00ff88" font-size="10">Java</text>
<rect x="330" y="568" width="38" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="349" y="582" text-anchor="middle" fill="#00ff88" font-size="10">PHP</text>

<!-- WEB + BACKEND -->
<rect x="32" y="598" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="612" fill="#a855f7" font-size="10" letter-spacing="2">// WEB + BACKEND</text>
<rect x="32" y="620" width="58" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="61" y="634" text-anchor="middle" fill="#00ff88" font-size="10">Django</text>
<rect x="98" y="620" width="52" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="124" y="634" text-anchor="middle" fill="#00ff88" font-size="10">MySQL</text>
<rect x="158" y="620" width="70" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="193" y="634" text-anchor="middle" fill="#00ff88" font-size="10">MongoDB</text>
<rect x="236" y="620" width="64" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="268" y="634" text-anchor="middle" fill="#00ff88" font-size="10">Firebase</text>
<rect x="308" y="620" width="60" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="338" y="634" text-anchor="middle" fill="#00ff88" font-size="10">Heroku</text>

<!-- DESIGN + VIZ -->
<rect x="32" y="650" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="664" fill="#a855f7" font-size="10" letter-spacing="2">// DESIGN + VIZ</text>
<rect x="32" y="672" width="52" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="58" y="686" text-anchor="middle" fill="#00ff88" font-size="10">Figma</text>
<rect x="92" y="672" width="62" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="123" y="686" text-anchor="middle" fill="#00ff88" font-size="10">Blender</text>
<rect x="162" y="672" width="84" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="204" y="686" text-anchor="middle" fill="#00ff88" font-size="10">Illustrator</text>
<rect x="254" y="672" width="46" height="20" rx="2" fill="#0a0a18" stroke="#2d1b4e" stroke-width="1"/><text x="277" y="686" text-anchor="middle" fill="#00ff88" font-size="10">D3.js</text>

<!-- PROMPT 4 skill_levels y=706 -->
<text x="32" y="726" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="726" fill="#00ff88" font-size="13">./skill_levels --bar --radar</text>

<!-- BARS y=750 -->
<rect x="32" y="736" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="750" fill="#a855f7" font-size="10" letter-spacing="2">// PROFICIENCY BARS</text>

<text x="52" y="772" fill="#c8ffd4" font-size="11">Embedded Systems</text><text x="628" y="772" text-anchor="end" fill="#00ff88" font-size="11">91%</text>
<rect x="52" y="777" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="777" height="5" fill="url(#gv)" class="b1"/>

<text x="52" y="800" fill="#c8ffd4" font-size="11">C / C++</text><text x="628" y="800" text-anchor="end" fill="#00ff88" font-size="11">88%</text>
<rect x="52" y="805" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="805" height="5" fill="url(#gv)" class="b2"/>

<text x="52" y="828" fill="#c8ffd4" font-size="11">Robotics / ROS</text><text x="628" y="828" text-anchor="end" fill="#00ff88" font-size="11">85%</text>
<rect x="52" y="833" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="833" height="5" fill="url(#gv)" class="b3"/>

<text x="52" y="856" fill="#c8ffd4" font-size="11">Python</text><text x="628" y="856" text-anchor="end" fill="#a855f7" font-size="11">80%</text>
<rect x="52" y="861" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="861" height="5" fill="url(#gv)" class="b4"/>

<text x="52" y="884" fill="#c8ffd4" font-size="11">Web Dev</text><text x="628" y="884" text-anchor="end" fill="#a855f7" font-size="11">74%</text>
<rect x="52" y="889" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="889" height="5" fill="url(#vv)" class="b5"/>

<text x="52" y="912" fill="#c8ffd4" font-size="11">Machine Learning</text><text x="628" y="912" text-anchor="end" fill="#a855f7" font-size="11">68%</text>
<rect x="52" y="917" width="400" height="5" fill="#0d0d1a"/>
<rect x="52" y="917" height="5" fill="url(#vv)" class="b6"/>

<!-- RADAR y=930 -->
<rect x="32" y="930" width="616" height="1" fill="#2d1b4e"/>
<text x="32" y="944" fill="#a855f7" font-size="10" letter-spacing="2">// PROFICIENCY RADAR</text>

<!-- Grid rings cx=340 cy=1104 r=110 -->
<polygon points="340,1076.5 363.8,1090.2 363.8,1117.8 340,1131.5 316.2,1117.8 316.2,1090.2" fill="none" stroke="#1a1a2e" stroke-width="1"/>
<polygon points="340,1049.0 387.6,1076.5 387.6,1131.5 340,1159.0 292.4,1131.5 292.4,1076.5" fill="none" stroke="#1a1a2e" stroke-width="1"/>
<polygon points="340,1021.5 411.4,1062.8 411.4,1145.2 340,1186.5 268.6,1145.2 268.6,1062.8" fill="none" stroke="#1a1a2e" stroke-width="1"/>
<polygon points="340,994.0 435.3,1049.0 435.3,1159.0 340,1214.0 244.7,1159.0 244.7,1049.0" fill="none" stroke="#2d1b4e" stroke-width="1"/>

<!-- Spokes -->
<line x1="340" y1="1104" x2="340" y2="994" stroke="#1a1a2e" stroke-width="1"/>
<line x1="340" y1="1104" x2="435.3" y2="1049" stroke="#1a1a2e" stroke-width="1"/>
<line x1="340" y1="1104" x2="435.3" y2="1159" stroke="#1a1a2e" stroke-width="1"/>
<line x1="340" y1="1104" x2="340" y2="1214" stroke="#1a1a2e" stroke-width="1"/>
<line x1="340" y1="1104" x2="244.7" y2="1159" stroke="#1a1a2e" stroke-width="1"/>
<line x1="340" y1="1104" x2="244.7" y2="1049" stroke="#1a1a2e" stroke-width="1"/>

<!-- Data polygon -->
<polygon points="340,1003.9 423.8,1055.6 421.0,1150.8 340,1192.0 269.5,1144.7 275.2,1066.6" fill="#a855f7" fill-opacity="0.18" stroke="#a855f7" stroke-width="1.5"/>

<!-- Dots -->
<circle cx="340" cy="1003.9" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="423.8" cy="1055.6" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="421.0" cy="1150.8" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="340" cy="1192.0" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="269.5" cy="1144.7" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="275.2" cy="1066.6" r="4" fill="#00ff88" stroke="#a855f7" stroke-width="1.5"/>
<circle cx="340" cy="1104" r="3" fill="#7c3aed"/>

<!-- Radar labels -->
<text x="340" y="978" text-anchor="middle" fill="#4a5568" font-size="11">Embedded</text>
<text x="461" y="1059" text-anchor="start" fill="#4a5568" font-size="11">C / C++</text>
<text x="461" y="1154" text-anchor="start" fill="#4a5568" font-size="11">Robotics</text>
<text x="340" y="1232" text-anchor="middle" fill="#4a5568" font-size="11">Python</text>
<text x="219" y="1154" text-anchor="end" fill="#4a5568" font-size="11">Web Dev</text>
<text x="219" y="1059" text-anchor="end" fill="#4a5568" font-size="11">ML / AI</text>

<!-- PROMPT 5 stats y=1268 -->
<text x="32" y="1288" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="1288" fill="#00ff88" font-size="13">github-cli stats NOXUSTIC</text>

<!-- STAT BOXES y=1296 -->
<rect x="32" y="1296" width="192" height="62" rx="4" fill="#0a0a10" stroke="#2d1b4e" stroke-width="1"/>
<text x="128" y="1325" text-anchor="middle" fill="#00ff88" font-size="22" font-weight="700">&#x221E;</text>
<text x="128" y="1348" text-anchor="middle" fill="#4a5568" font-size="10" letter-spacing="1">COMMITS</text>

<rect x="244" y="1296" width="192" height="62" rx="4" fill="#0a0a10" stroke="#2d1b4e" stroke-width="1"/>
<text x="340" y="1325" text-anchor="middle" fill="#a855f7" font-size="22" font-weight="700">17</text>
<text x="340" y="1348" text-anchor="middle" fill="#4a5568" font-size="10" letter-spacing="1">ROBOTS BUILT</text>

<rect x="456" y="1296" width="192" height="62" rx="4" fill="#0a0a10" stroke="#2d1b4e" stroke-width="1"/>
<text x="552" y="1325" text-anchor="middle" fill="#00ff88" font-size="22" font-weight="700">404</text>
<text x="552" y="1348" text-anchor="middle" fill="#4a5568" font-size="10" letter-spacing="1">SLEEP NOT FOUND</text>

<!-- PROMPT 6 links y=1378 -->
<text x="32" y="1398" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="1398" fill="#00ff88" font-size="13">cat ./links.conf</text>

<text x="52" y="1420" fill="#a855f7" font-size="12">&#x2192;</text><text x="68" y="1420" fill="#4a5568" font-size="12">portfolio   :</text><text x="180" y="1420" fill="#00ff88" font-size="12">saadat-five.vercel.app</text>
<text x="52" y="1438" fill="#a855f7" font-size="12">&#x2192;</text><text x="68" y="1438" fill="#4a5568" font-size="12">company     :</text><text x="180" y="1438" fill="#00ff88" font-size="12">botengineersbd.com</text>
<text x="52" y="1456" fill="#a855f7" font-size="12">&#x2192;</text><text x="68" y="1456" fill="#4a5568" font-size="12">linkedin    :</text><text x="180" y="1456" fill="#00ff88" font-size="12">saadat-s-rahman</text>
<text x="52" y="1474" fill="#a855f7" font-size="12">&#x2192;</text><text x="68" y="1474" fill="#4a5568" font-size="12">github      :</text><text x="180" y="1474" fill="#00ff88" font-size="12">github.com/NOXUSTIC</text>

<!-- PROMPT 7 status y=1504 -->
<text x="32" y="1524" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<text x="222" y="1524" fill="#00ff88" font-size="13">echo $STATUS</text>

<text x="52" y="1548" fill="#00ff88" font-size="12">&#x25B8;</text><text x="68" y="1548" fill="#4a5568" font-size="12">Currently:</text><text x="158" y="1548" fill="#c8ffd4" font-size="12">Learning ML &amp; AI</text>
<text x="52" y="1566" fill="#00ff88" font-size="12">&#x25B8;</text><text x="68" y="1566" fill="#4a5568" font-size="12">Open to:</text><text x="158" y="1566" fill="#c8ffd4" font-size="12">Hardware x Software collabs</text>
<text x="52" y="1584" fill="#a855f7" font-size="12">&#x25B8;</text><text x="68" y="1584" fill="#4a5568" font-size="12">Building:</text><text x="158" y="1584" fill="#a855f7" font-size="12">something that moves...</text>

<!-- FINAL PROMPT + CURSOR y=1606 -->
<text x="32" y="1606" fill="#a855f7" font-size="13" font-weight="700">noxustic@BOT-ENG:~$</text>
<rect x="222" y="1593" width="8" height="14" fill="#00ff88" class="blink"/>

</svg>
SVGEOF
echo "Done. Size: $(wc -c < /mnt/user-data/outputs/profile-card.svg) bytes"

