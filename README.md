
<!-- msc3.0_tagline_animated.svg -->
<svg viewBox="0 0 1200 180" width="100%" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title desc" preserveAspectRatio="xMidYMid slice">
  <title id="title">MSC3.0 | Meta Solution Corporation — Animated Tagline</title>
  <desc id="desc">Animated gradient tagline with subtle glow and data orbs.</desc>

  <!-- Gradient -->
  <defs>
    <linearGradient id="msc3g" x1="0" y1="0" x2="1200" y2="180" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#00C8FF">
        <animate attributeName="stop-color" values="#00C8FF;#2AF598;#00C8FF" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#2AF598">
        <animate attributeName="stop-color" values="#2AF598;#00C8FF;#2AF598" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Soft glow filter -->
    <filter id="glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Motion path for orbs -->
    <path id="orbit" d="M60,120 C300,20 900,20 1140,120" fill="none"/>
  </defs>

  <!-- Background pulse line -->
  <path d="M60,120 C300,20 900,20 1140,120" stroke="url(#msc3g)" stroke-width="2" fill="none" opacity="0.4">
    <animate attributeName="opacity" values="0.25;0.6;0.25" dur="5s" repeatCount="indefinite"/>
  </path>

  <!-- Moving data orbs -->
  <circle r="3" fill="#FFFFFF">
    <animateMotion dur="8s" repeatCount="indefinite" rotate="auto">
      <mpath href="#orbit"/>
    </animateMotion>
  </circle>
  <circle r="3" fill="#FFFFFF" opacity="0.7">
    <animateMotion dur="8s" begin="2s" repeatCount="indefinite" rotate="auto">
      <mpath href="#orbit"/>
    </animateMotion>
  </circle>

  <!-- Main tagline -->
  <g filter="url(#glow)">
    <text x="50%" y="68" text-anchor="middle" font-size="28" font-family="Segoe UI, Roboto, Ubuntu, Arial, sans-serif" fill="#FFFFFF" font-weight="700">
      M. Hassan Sohail Naqi • MSC3.0 | Meta Solution Corporation
      <animate attributeName="letter-spacing" values="0;1.5;0" dur="5s" repeatCount="indefinite"/>
    </text>

    <text x="50%" y="118" text-anchor="middle" font-size="22" font-family="Segoe UI, Roboto, Ubuntu, Arial, sans-serif" fill="#FFFFFF" opacity="0.9">
      Where AI Agents Build the Future
      <animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Underline sweep -->
  <rect x="160" y="132" width="880" height="2" fill="url(#msc3g)">
    <animate attributeName="x" values="160;160;160" dur="0s" repeatCount="indefinite"/>
    <animate attributeName="width" values="0;880;0" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

---
<p align="center">
  <img src="https://raw.githubusercontent.com/MetaSolutionCorp/assets/main/msc3.0_tagline_animated.svg" alt="MSC3.0 animated tagline" width="100%" />
</p>

---

### 🧠 About Me
- 🔭 Currently working at **MSc3.0 | META SOLUTION CORPORATION**
- 🌱 Learning and building with **Next.js 13**, **React Native**, and **Agentic AI Systems**
- 👯 Collaborating with **Panaverse DAO** on AI-native architectures
- 💡 Exploring **Dapr**, **OpenAI Agents SDK**, and **Kubernetes Cloud Ascent**
- 📫 Contact: **metasolutionscorp@gmail.com**

---

### 🌐 Connect With Me
<p align="center">
  <a href="mailto:metasolutionscorp@gmail.com"><img src="https://img.icons8.com/fluency/48/gmail-new.png" alt="Gmail"/></a>
  <a href="https://linkedin.com/in/hasansohailnaqi"><img src="https://img.icons8.com/color/48/linkedin.png" alt="LinkedIn"/></a>
  <a href="https://github.com/hasansohailnaqi"><img src="https://img.icons8.com/ios-filled/48/00C8FF/github.png" alt="GitHub"/></a>
  <a href="https://x.com/"><img src="https://img.icons8.com/ios-filled/48/00C8FF/twitterx--v1.png" alt="Twitter"/></a>
</p>

---

### 🧰 Languages & Tools
<details open>
<summary>Click to expand the stack</summary>

<p align="center">
  <a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="45" height="45"/></a>
  <a href="https://nextjs.org/"><img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" width="45" height="45"/></a>
  <a href="https://nodejs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="45" height="45"/></a>
  <a href="https://python.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="45" height="45"/></a>
  <a href="https://firebase.google.com/"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="45" height="45"/></a>
  <a href="https://aws.amazon.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="45" height="45"/></a>
  <a href="https://azure.microsoft.com/"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" width="45" height="45"/></a>
  <a href="https://docker.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="45" height="45"/></a>
  <a href="https://kubernetes.io/"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" width="45" height="45"/></a>
  <a href="https://dapr.io/"><img src="https://dapr.io/images/dapr.svg" width="45" height="45"/></a>
  <a href="https://www.tensorflow.org/"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" width="45" height="45"/></a>
  <a href="https://flutter.dev/"><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" width="45" height="45"/></a>
  <a href="https://typescriptlang.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="45" height="45"/></a>
</p>
</details>

---

### 📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hasansohailnaqi&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hasansohailnaqi&layout=compact&theme=tokyonight&hide_border=true" height="150"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hasansohailnaqi&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

### 🏆 GitHub Achievements
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=hasansohailnaqi&theme=darkhub&column=6&margin-w=10&margin-h=10" />
</p>

---

### 🌌 Vision
> “We don’t just build products — we create digital realities powered by intelligence and imagination.”  
> **— Meta Solution Corporation (MSC3.0)**

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&color=00C8FF&size=24&center=true&vCenter=true&width=600&lines=🚀+MSC3.0+|+MetaSolutionCorp;AI+Driven+Innovation+for+the+Next+Era;💠+Where+Agents+Build+the+Future" />
</p>

<p align="center">
  <b>🌐 Visit:</b> <a href="https://metasolutioncorp.com">Msc3.0</a> | <b>📧 Email:</b> metasolutionscorp@gmail.com
</p>

---
