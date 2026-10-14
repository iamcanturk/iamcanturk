<div align="center">

<a href="https://iamcanturk.dev/en/"><img src="assets/header.svg" width="100%" alt="whoami: Can Türk. Full-stack developer focused on application security. I build first, then try to break it. Bursa, TR · AppSec Engineer @ Kuark"></a>

<a href="https://iamcanturk.dev"><img src="https://img.shields.io/badge/web-iamcanturk.dev-4f6bff?style=for-the-badge&labelColor=151a31&logo=googlechrome&logoColor=a4b5ff" alt="Website: iamcanturk.dev"></a>
<a href="https://x.com/iamcanturk"><img src="https://img.shields.io/badge/x-@iamcanturk-2a3161?style=for-the-badge&labelColor=151a31&logo=x&logoColor=f2f4ff" alt="X: @iamcanturk"></a>
<a href="https://www.instagram.com/iamcanturk.dev/"><img src="https://img.shields.io/badge/instagram-@iamcanturk.dev-b04dff?style=for-the-badge&labelColor=151a31&logo=instagram&logoColor=cbb5ff" alt="Instagram: @iamcanturk.dev"></a>
<a href="https://www.tiktok.com/@iamcanturk.dev"><img src="https://img.shields.io/badge/tiktok-@iamcanturk.dev-ff3d71?style=for-the-badge&labelColor=151a31&logo=tiktok&logoColor=ffb0b8" alt="TikTok: @iamcanturk.dev"></a>
<a href="https://www.linkedin.com/in/yusufcanturk/"><img src="https://img.shields.io/badge/linkedin-yusufcanturk-9466ff?style=for-the-badge&labelColor=151a31&logo=linkedin&logoColor=cbb5ff" alt="LinkedIn: yusufcanturk"></a>

I'm a full-stack developer focused on application security, working as an<br>
**Application Security Engineer at Kuark** in Bursa, Türkiye.<br>
I build first, then try to break what I built, and I tell the vendor when I find a hole in software I use.<br>
The rest of the time I design the brands and interfaces that sit on top of it all.

<sub><b>TR</b> · Uygulama güvenliğine yoğunlaşmış bir fullstack geliştiriciyim. Önce yazıp sonra kırmayı deniyorum.</sub>

</div>

<br>

<img src="assets/title-projects.svg" width="100%" alt="ls ~/projects: Things I have built (3 projects)">

<table>
  <tr>
    <td width="33%" valign="top" align="center">
      <img src="assets/desk_monitor.png" height="120" alt="Pixel mascot at a desk with a monitor"><br>
      <a href="https://github.com/iamcanturk/DoctorDock"><b>DoctorDock</b></a><br>
      <sub><i>A doctor for your Docker</i></sub>
    </td>
    <td width="33%" valign="top" align="center">
      <img src="assets/magnify.png" height="120" alt="Pixel mascot with a magnifying glass"><br>
      <a href="https://github.com/iamcanturk/erklig"><b>Erklig</b></a><br>
      <sub><i>Mighty backdoor analysis engine</i></sub>
    </td>
    <td width="33%" valign="top" align="center">
      <img src="assets/laptop.png" height="120" alt="Pixel mascot with a laptop and a coffee"><br>
      <a href="https://github.com/iamcanturk/mergenflow"><b>MergenFlow</b></a><br>
      <sub><i>The freelancer OS</i></sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      Scans your local Docker environment for security problems, misconfigurations and reclaimable disk in under a second, entirely offline. Ranks findings by severity and gives you a health score out of 100.<br><br>
      <code>Go</code> <code>Docker</code> <code>macOS</code> <code>MIT</code><br>
      <sub><a href="https://doctordock.iamcanturk.dev">doctordock.iamcanturk.dev</a> · <a href="https://iamcanturk.dev/en/proje/doctordock-a-doctor-for-your-docker/">project page</a></sub>
    </td>
    <td valign="top">
      An open-source tool for detecting web shells and backdoors on servers, using signature and behaviour based analysis. Fast triage during penetration tests and incident response.<br><br>
      <code>Go</code> <code>DFIR</code> <code>Pentest</code><br>
      <sub><a href="https://iamcanturk.dev/en/proje/erklig-mighty-backdoor-analysis-engine/">project page</a></sub>
    </td>
    <td valign="top">
      An open-source SaaS for freelancers that combines financial projection, recurring budget management and Kanban workflow tracking in one place. <i>In development.</i><br><br>
      <code>TypeScript</code> <code>SaaS</code><br>
      <sub><a href="https://iamcanturk.dev/en/proje/mergenflow-the-freelancer-os/">project page</a></sub>
    </td>
  </tr>
</table>

<sub>Most of my client and enterprise work is under NDA. These are the ones I can share openly.</sub>

<br>

<img src="assets/title-security.svg" width="100%" alt="nmap -sV ~/findings: Security research (2 CVEs)">

When I find a vulnerability in software I use, I tell the vendor. Once a fix ships, I publish it.

<table>
  <thead>
    <tr><th align="left">CVE</th><th align="left">Vulnerability</th><th align="left">CVSS</th><th align="left">Affected</th><th align="left">References</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://iamcanturk.dev/en/security/cve-2026-28403/"><b>CVE-2026-28403</b></a></td>
      <td>Missing WebSocket origin validation<br><sub>Cross-Site WebSocket Hijacking</sub></td>
      <td><img src="https://img.shields.io/badge/7.6-HIGH-ff5c6c?style=flat-square&labelColor=151a31" alt="CVSS 7.6 HIGH"></td>
      <td>Textream (macOS) &lt; 1.5.1</td>
      <td><a href="https://iamcanturk.dev/en/security/cve-2026-28403/">Write-up</a> · <a href="https://nvd.nist.gov/vuln/detail/CVE-2026-28403">NVD</a> · <a href="https://github.com/advisories/GHSA-wr3v-x247-337w">GHSA</a></td>
    </tr>
    <tr>
      <td><a href="https://iamcanturk.dev/en/security/cve-2026-28412/"><b>CVE-2026-28412</b></a></td>
      <td>Resource exhaustion through unlimited connections<br><sub>Denial of Service</sub></td>
      <td><img src="https://img.shields.io/badge/6.5-MEDIUM-ffa24d?style=flat-square&labelColor=151a31" alt="CVSS 6.5 MEDIUM"></td>
      <td>Textream (macOS) &lt; 1.5.1</td>
      <td><a href="https://iamcanturk.dev/en/security/cve-2026-28412/">Write-up</a> · <a href="https://nvd.nist.gov/vuln/detail/CVE-2026-28412">NVD</a> · <a href="https://github.com/advisories/GHSA-qr5p-7x47-qxh9">GHSA</a></td>
    </tr>
  </tbody>
</table>

<br>

<img src="assets/title-shorts.svg" width="100%" alt="./pixel-shorts --all: Pixel Shorts (30 episodes)">

<table>
  <tr>
    <td valign="middle" align="center" width="150">
      <img src="assets/present.png" height="120" alt="Pixel mascot presenting">
    </td>
    <td valign="middle">
      <b>30 seconds a day on software, AI, tech and security.</b><br>
      Short pixel-art videos: vibe-coding pitfalls, password managers, AI agents, famous moments in tech history and a Republic Day special. The videos are in Turkish; every episode's script and checklist live on the site.<br><br>
      <img src="https://img.shields.io/badge/starts-20%20Oct%202026-ffc94a?style=flat-square&labelColor=151a31" alt="Starts 20 Oct 2026">&nbsp;
      <a href="https://iamcanturk.dev/en/shorts/"><b>iamcanturk.dev/en/shorts →</b></a><br>
      Watch on <a href="https://www.tiktok.com/@iamcanturk.dev">TikTok</a> · <a href="https://www.instagram.com/iamcanturk.dev/">Instagram</a> · <a href="https://x.com/iamcanturk">X</a><br>
      <sub><b>TR</b> · Her gün 30 saniyede yazılım, yapay zekâ, teknoloji ve güvenlik.</sub>
    </td>
  </tr>
</table>

<br>

<img src="assets/title-notebook.svg" width="100%" alt="cat ~/notes/*.md: Notebook (2 posts)">

Long-form notes on security, software and AI.

- `2026-08-14` &nbsp;**[I Wrote a Doctor for My Docker](https://iamcanturk.dev/en/i-wrote-a-doctor-for-my-docker/)** <sub>· [TR](https://iamcanturk.dev/dockerima-bir-doktor-yazdim/)</sub><br>
  <sub>I used Docker every day but had no idea what was inside it. So I wrote DoctorDock.</sub>
- `2026-08-09` &nbsp;**[Reverse Development in the Age of AI](https://iamcanturk.dev/en/reverse-development-in-the-age-of-ai/)** <sub>· [TR](https://iamcanturk.dev/ai-caginda-tersine-gelisim/)</sub><br>
  <sub>I sat down to write after a long break and noticed I can't think as well as I used to. What is AI doing to the way we think?</sub>

<sub>Subscribe via [RSS](https://iamcanturk.dev/en/rss.xml).</sub>

<br>

<img src="assets/title-stack.svg" width="100%" alt="whoami --long: What I do">

```text
software   PHP · Laravel · TypeScript · Go · MySQL
security   OWASP Top 10 · SANS 25 · Pentest · Threat modeling
design     Logo · Brand identity · Social media · UI/UX
```

<p>
  <img src="https://img.shields.io/badge/PHP-151a31?style=for-the-badge&logo=php&logoColor=a4b5ff" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-151a31?style=for-the-badge&logo=laravel&logoColor=ff5c6c" alt="Laravel">
  <img src="https://img.shields.io/badge/TypeScript-151a31?style=for-the-badge&logo=typescript&logoColor=4f6bff" alt="TypeScript">
  <img src="https://img.shields.io/badge/Go-151a31?style=for-the-badge&logo=go&logoColor=9ef2c3" alt="Go">
  <img src="https://img.shields.io/badge/MySQL-151a31?style=for-the-badge&logo=mysql&logoColor=ffc94a" alt="MySQL">
  <img src="https://img.shields.io/badge/Docker-151a31?style=for-the-badge&logo=docker&logoColor=a4b5ff" alt="Docker">
</p>

<br>

<div align="center">

<sub>It started with running network cables in 2015; today I report CVEs.</sub><br>
**[iamcanturk.dev](https://iamcanturk.dev/en/)** · projects, writing and how to reach me.

</div>
