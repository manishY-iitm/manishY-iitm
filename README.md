<div align="center">

# 👨‍💻 Manish Yadav
### *Computer Science @ IIT Madras*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Systems+Programming+%26+Linux+Internals;Low-Latency+Networking+%26+Raw+UDP+Sockets;Passionate+Open-Source+Builder+%26+GSoC+Aspirant;Modern+C%2B%2B%2C+Rust%2C+and+POSIX+Userspace)](https://git.io/typing-svg)

<p align="center">
  <a href="mailto:manishyadav27480@gmail.com"><img src="https://img.shields.io/badge/Email-manishyadav27480%40gmail.com-blue?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/manishY-iitm"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://github.com/manishY-iitm/My-Portfolio"><img src="https://img.shields.io/badge/Portfolio-Live_Showcase-00C7B7?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"></a>
</p>

</div>

---

### ⚡ Executive Summary & OS / Systems Philosophy

I am a computer science student at **IIT Madras** passionate about **Operating Systems internals, low-latency systems, and open-source software engineering**. I love peeling back layers of abstraction:
- Moving beyond browser abstractions down to **raw POSIX sockets**, **WASAPI/CoreAudio driver interfaces**, and **custom UDP framing**.
- Building **deterministic, zero-cost userspace daemons** integrated directly into Linux desktop environments (Wayland/GNOME) via Unix domain sockets.
- Believing in the **Open Source ethos**: transparent roadmaps, clean commit history, RFC-driven architectures, and building public tools that empower fellow developers.

---

### 🚀 Flagship Systems & Open-Source Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🔊 <a href="https://github.com/manishY-iitm/lan-audio">LAN Audio</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=white" alt="Rust"/>
        <img src="https://img.shields.io/badge/OS_Audio-WASAPI%20%7C%20CoreAudio-00599C?style=flat-square" alt="Audio APIs"/>
        <img src="https://img.shields.io/badge/Networking-Raw_UDP-blueviolet?style=flat-square" alt="UDP"/>
        <img src="https://img.shields.io/badge/Latency-%3C20ms-success?style=flat-square" alt="Latency"/>
      </p>
      <p><b>Native Ultra-Low-Latency Wireless Speaker System:</b></p>
      <ul>
        <li>Bypasses Chrome/WebRTC capture pipelines (which suffer mandatory 100–300ms buffering delays) by capturing system audio directly at the kernel driver layer via <b>WASAPI loopback</b> on Windows and feeding <b>CoreAudio</b> on macOS.</li>
        <li>Implements custom UDP packet protocol with sequence tracking, microsecond timestamping, and <b>Opus LowDelay</b> encoding for true real-time streaming.</li>
      </ul>
      <p align="center"><b><a href="https://github.com/manishY-iitm/lan-audio">Explore Repository & Architecture →</a></b></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⏱️ <a href="https://github.com/manishY-iitm/Pomodoro">Pomodoro OS Daemon</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Linux-GNOME_Shell_50-FCC624?style=flat-square&logo=linux&logoColor=black" alt="GNOME"/>
        <img src="https://img.shields.io/badge/Session-Wayland-red?style=flat-square" alt="Wayland"/>
        <img src="https://img.shields.io/badge/IPC-Unix_Domain_Socket-00599C?style=flat-square" alt="IPC"/>
        <img src="https://img.shields.io/badge/Database-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
      </p>
      <p><b>Native Linux Desktop Timer & IPC Daemon:</b></p>
      <ul>
        <li>Engineered natively for <b>Kali Linux GNOME on Wayland</b> with a GNOME Shell ESM extension and borderless RGBA TrueColor dock widget.</li>
        <li>Unified background daemon communicates over <code>/run/user/1000/pomodoro/pomodoro.sock</code> with <code>time.monotonic()</code> drift-free clock guarantees and SQLite session persistence.</li>
      </ul>
      <p align="center"><b><a href="https://github.com/manishY-iitm/Pomodoro">Explore Repository & Architecture →</a></b></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🌐 <a href="https://github.com/manishY-iitm/GSoC">GSoC Launchpad</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Open_Source-GSoC-4285F4?style=flat-square&logo=google&logoColor=white" alt="GSoC"/>
        <img src="https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js&logoColor=white" alt="Next.js"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      </p>
      <p><b>Interactive Open-Source Readiness Platform:</b></p>
      <ul>
        <li>Comprehensive 10-stage preparation roadmap guiding student developers from zero open-source experience to Google Summer of Code readiness.</li>
        <li>Features verified official documentation links, interactive milestone tracking, proposal checklists, and local JSON exportable progress.</li>
      </ul>
      <p align="center"><b><a href="https://github.com/manishY-iitm/GSoC">Explore Repository →</a></b></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🧭 <a href="https://github.com/manishY-iitm/Student-Manager">COMPASS Navigator</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
        <img src="https://img.shields.io/badge/Architecture-10_Pathways-orange?style=flat-square" alt="Pathways"/>
      </p>
      <p><b>Personal Technical Learning Navigator:</b></p>
      <ul>
        <li>Curriculum diagnostic engine featuring deep technical tracks: Systems Programming & C++, Linux Engineering & Cloud Infra, Distributed Systems, and Low-Latency HFT.</li>
        <li>Adaptive placement algorithms evaluate code comprehension to eliminate redundant beginner coursework.</li>
      </ul>
      <p align="center"><b><a href="https://github.com/manishY-iitm/Student-Manager">Explore Repository →</a></b></p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Stack & Systems Toolchain

<table>
  <tr>
    <td align="left" width="25%"><b>Core & Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Modern_C++_(C++20)-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/>
      <img src="https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="left"><b>OS & Linux Internals</b></td>
    <td>
      <img src="https://img.shields.io/badge/Linux_Kernel_Userspace-FCC624?style=flat-square&logo=linux&logoColor=black"/>
      <img src="https://img.shields.io/badge/POSIX_APIs-333333?style=flat-square&logo=gnu&logoColor=white"/>
      <img src="https://img.shields.io/badge/Unix_Domain_Sockets-2088FF?style=flat-square"/>
      <img src="https://img.shields.io/badge/Bash_%2F_Zsh-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white"/>
      <img src="https://img.shields.io/badge/Wayland_%2F_X11-FF6600?style=flat-square"/>
      <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="left"><b>Networking & Audio</b></td>
    <td>
      <img src="https://img.shields.io/badge/Raw_UDP_%2F_TCP_Sockets-007ACC?style=flat-square"/>
      <img src="https://img.shields.io/badge/WASAPI_Loopback-0078D4?style=flat-square&logo=windows&logoColor=white"/>
      <img src="https://img.shields.io/badge/CoreAudio-999999?style=flat-square&logo=apple&logoColor=white"/>
      <img src="https://img.shields.io/badge/Opus_Codec-3A833A?style=flat-square"/>
      <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="left"><b>Git, Open Source & Web</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/React_19_%2F_Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
    </td>
  </tr>
</table>

---

### 🌐 Open Source Contributions & Community Engagement

- 🌟 **Active Open Source Contributor:**
  - Contributed to [`ScalerOpenSourceLabsOrg/osc-learners`](https://github.com/manishY-iitm/osc-learners) and [`first-contributions`](https://github.com/manishY-iitm/first-contributions).
  - Maintained upstream sync, atomic commit hygiene, feature branching, and clean PR descriptions.
- 🎯 **GSoC & FOSS Club Aspirations:**
  - Actively targeting Google Summer of Code (GSoC) organizations focusing on Systems, Networking, and Infrastructure tooling.
  - Creator of **GSoC Launchpad**, sharing resources and structured preparation workflows with fellow students.
- 🤝 **What I Bring to the College OS Club:**
  - **Systems Hands-on:** Practical experience building kernel loopback streaming, Wayland desktop daemons, and low-latency network protocols.
  - **Team Collaboration:** Enthusiastic about peer code reviews, mentoring junior club members on Git workflows, and contributing to club projects.
  - **Drive & Curiosity:** Eager to tackle kernel modules, distributed systems, embedded Linux, and club infrastructure.

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=manishY-iitm&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="Manish's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=manishY-iitm&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</div>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=manishY-iitm&theme=tokyonight&hide_border=true" width="97%" alt="Streak Stats" />
</p>

---

<div align="center">
  <sub>Built with ☕, Linux, and Modern C++ / Rust. Always open to discussing systems engineering and open-source collaborations.</sub>
</div>
