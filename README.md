<!-- ==================== CSS ==================== -->
<style>
/* ==== توهج نابض للبانر والصور ==== */
@keyframes glowPulse {
  0%, 100% { filter: drop-shadow(0 0 6px rgba(0,255,255,0.25)); }
  50% { filter: drop-shadow(0 0 22px rgba(0,255,255,0.85)); }
}

/* ==== تأثير ليزر متحرك فوق الصور ==== */
@keyframes laserSweep {
  0% { background-position: -200% 0; }
  50% { background-position: 200% 0; }
  100% { background-position: 200% 0; }
}

/* ==== بانر الصورة الرئيسية ==== */
.banner-glow {
  position: relative;
  display: inline-block;
  animation: glowPulse 4s infinite ease-in-out;
  transition: transform 0.4s ease;
  border-radius: 15px;
  overflow: hidden;
}

.banner-glow:hover {
  transform: scale(1.05);
}

.banner-glow::after {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: linear-gradient(
    120deg,
    transparent 30%,
    rgba(255,255,255,0.25) 50%,
    transparent 70%
  );
  background-size: 200% 100%;
  animation: laserSweep 6s infinite linear;
  border-radius: 15px;
  pointer-events: none;
}

/* ==== توقيع نهائي متحرك ==== */
.footer-signature {
  color: #00ADB5;
  font-weight: 600;
  font-family: Consolas, monospace;
  text-shadow: 0 0 10px rgba(0,255,255,0.55), 0 0 20px rgba(0,255,255,0.35);
  animation: glowPulse 5s infinite ease-in-out;
  margin-top: 20px;
  letter-spacing: 1px;
}
</style>

<!-- ==================== HEADER ==================== -->
<div style="background: linear-gradient(180deg, #0f1115 0%, #1a1f27 100%); padding: 30px 20px; border-radius: 20px;" align="center">

  <!-- ======= بانر توقيع رقمي متحرك ======= -->
  <div style="padding:12px; border-radius:20px; background: linear-gradient(90deg, #00ADB5, #00696E); box-shadow: 0 0 32px rgba(0,173,181,0.65); display:inline-block; width:100%; max-width:1100px;">
    <div class="banner-glow">
      <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/main/branding/alaa10.png"
           width="85%" alt="Alaa Mahmoud Digital Signature Banner"
           style="display:block; border-radius:15px;"/>
    </div>
  </div>

  <!-- ======= التعريف الشخصي ======= -->
  <h2 style="color:#00ADB5; margin-top: 20px;">👋 Hi, I'm <span style="color:#00E0C7;">Alaa Mahmoud Mohamed</span></h2>

  <!-- ======= تأثير الكتابة ======= -->
  <a href="https://readme-typing-svg.demolab.com/demo/?lines=Cybersecurity+Analyst;AI+Tools+Developer;Ethical+Hacker;Defensive+Systems+Engineer" target="_blank">
    <img src="https://readme-typing-svg.demolab.com?font=Consolas&weight=600&size=24&pause=1000&color=00ADB5&center=true&vCenter=true&width=600&lines=Cybersecurity+Analyst;AI+Tools+Developer;Ethical+Hacker;Defensive+Systems+Engineer" alt="Typing Animation" />
  </a>

  <p style="color:#cfd8dc; margin-top:10px;">📍 Cairo, Egypt  &nbsp; • &nbsp; 💬 “Security through Knowledge — Knowledge through Sharing”</p>

  <!-- ======= روابط التواصل ======= -->
  <p>
    <a href="https://www.linkedin.com/in/alaa-mahmoud-/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
    <a href="https://github.com/Alaamahm0ud" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    <a href="mailto:alaa.m.egypt@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
    </a>
  </p>

  <hr style="opacity:0.28; margin-top:22px;">

  <!-- ======= نبذة عني ======= -->
  ## 🧠 About Me
  Cybersecurity developer specializing in AI-driven defensive systems and bilingual documentation.  
  I create secure, open-source tools tailored for Arabic-speaking professionals, bridging human insight and machine learning in threat defense.

  <hr style="opacity:0.28;">

  <!-- ======= التقنية ======= -->
  ## ⚙️ Technical Stack
  <div align="center">
    ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust)
    ![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
    ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
    ![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
    ![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=mysql)
    ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell)
    ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
  </div>

  <hr style="opacity:0.28;">

  <!-- ======= المشاريع المميزة ======= -->
  ## 🚀 Featured Projects
  <div align="center">
    <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/main/branding/CSG1.jpg" width="280" alt="Project 1" style="border-radius:15px; box-shadow:0 6px 16px rgba(0,0,0,0.45);"/>
    <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/main/branding/CSG.jpg" width="330" alt="Main Project" style="margin: 0 15px; border-radius:20px; box-shadow:0 6px 20px rgba(0,173,181,0.55);"/>
    <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/main/branding/CSG.04.png" width="280" alt="Project 3" style="border-radius:15px; box-shadow:0 6px 16px rgba(0,0,0,0.45);"/>
  </div>

  <hr style="opacity:0.28;">

  <!-- ======= التفاعل الشخصي ======= -->
  <div align="center">
    <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/output/github-contribution-grid-snake.svg" alt="Snake Animation" width="100%"/>
    <h3 style="color:#00ADB5; font-weight:600; margin-top:12px;">⭐ Always Learning — Always Building ⭐</h3>
    <sub style="color:gray;">Securing Tomorrow, One Line of Code at a Time.</sub>

    <br><br>
    <img src="https://raw.githubusercontent.com/Alaamahm0ud/Alaamahm0ud/main/branding/CSG.jpg" width="160" alt="CSG Logo" style="border-radius:20px; box-shadow:0 2px 12px rgba(0,0,0,0.4);"/>
    <div class="footer-signature">Secured by CSG Framework — 2025</div>
  </div>

</div>
