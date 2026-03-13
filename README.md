<div align="center">

<!-- Logo -->
<img src="assets/logo.png" alt="SEAGuard Logo" width="180" />

<h1>SEAGuard</h1>

<p><strong>Enhancing Disaster Preparedness and Community Resilience Across ASEAN Through AI and Real-Time Data</strong></p>

<p>
  <a href="https://seaguard.netlify.app/"><img src="https://img.shields.io/badge/Web-Live%20Demo-blue?style=for-the-badge&logo=netlify" alt="Web Demo"/></a>
  <a href="https://drive.google.com/drive/folders/1mtSj_nQmXwJLVnQTn9R34xf5T2Km5tDt?usp=sharing"><img src="https://img.shields.io/badge/Android-Download%20APK-green?style=for-the-badge&logo=android" alt="Download APK"/></a>
  <img src="https://img.shields.io/badge/Built%20for-Borneo%20Hackwknd%202025-orange?style=for-the-badge" alt="Borneo Hackwknd"/>
</p>

<p>
  Built for <a href="https://www.borneohackwknd.org/"><strong>Borneo Hackwknd</strong></a> — Southeast Asia's premier hackathon for solving regional challenges through technology.
</p>

</div>

---

## Report and Video

| | Link |
|---|---|
| **Report** | Coming soon |
| **Demo Video** | Coming soon |

---

## Problem Statement

Southeast Asia is one of the most disaster-prone regions in the world. The ASEAN region faces escalating threats from hydrometeorological hazards — particularly **floods, storms, and landslides** — that are intensifying due to climate change.

> **"Southeast Asia has experienced at least 1,575 hydrometeorological disasters since 1900, with floods and storms being the most frequent events. The occurrence of these disasters has significantly increased over the past 30 years."**
>
> — *ASEAN Trend Report DM 10 (2025)*

> **"More than 2,900 flood events were recorded between 2012 and 2022 across ASEAN member states."**
>
> — *ASEAN Trend Report DM 10 (2025)*

> **"In 2025 alone, floods and landslides across Indonesia, Thailand, and Malaysia resulted in over 1,100 fatalities, displaced hundreds of thousands of residents, and generated more than US$20 billion in economic losses."**
>
> — *ASEAN Regional Disaster Reports (2025)*

Despite the scale of these disasters, communities across ASEAN still struggle with:

- **Fragmented information** — risk warnings and evacuation procedures scattered across multiple institutions and platforms
- **Reactive response** — communities act only *after* disasters strike rather than preparing proactively
- **Limited evacuation guidance** — individuals don't know which routes are safe or which authorities to contact
- **Language barriers** — disaster platforms primarily use English, limiting accessibility for local communities
- **No localized risk forecasting** — existing tools focus on global-scale events, missing community-level hazards

---

## Solution

SEAGuard is an **AI-powered disaster management platform** that bridges these gaps by combining artificial intelligence, geospatial mapping, and real-time data to deliver **localized risk forecasts, early warning alerts, and evacuation guidance** to communities across ASEAN.

SEAGuard is available as **two complementary products**:

<!-- Platform Preview -->
<div align="center">
  <img src="assets/seaguard-platform.png" alt="SEAGuard Web App" width="700"/>
  <br/>
  <em>SEAGuard Web Dashboard &amp; Mobile App</em>
</div>

<br/>

### Web Platform

An interactive dashboard for regional situational awareness. It displays an **Active Zones Map** with real-time disaster zones (Evacuation, Caution, Danger), AI-powered **risk forecasts** for floods and landslides, and centralized **early warning alerts**. Users also get access to an **AI Chatbot**, offline survival guides, and emergency contacts — all in 9 ASEAN languages.

### Mobile App

A location-aware companion app for on-the-ground emergency support. It features **AR-Guided Navigation** to the nearest safe zones, and a **Disaster Simulator** with an AI Voice Guide (Gemini) and quiz gamification for preparedness training. Users can submit **Community Reports** with AI-powered hazard scanning from photos, and receive crowdsourced real-time alerts from nearby users.

---

## SDG Targets

SEAGuard directly contributes to three United Nations Sustainable Development Goals:

<div align="center">

| SDG | Goal | How SEAGuard Contributes |
|:---:|---|---|
| **SDG 13** | Climate Action | AI-driven early warning and predictive analytics to strengthen adaptive capacity against climate-related hazards |
| **SDG 4** | Quality Education | Accessible disaster e-learning modules, survival guides, and curated news for community preparedness |
| **SDG 11** | Sustainable Cities & Communities | Geospatial risk mapping, community reporting, and disaster communication tools for safer urban and rural areas |

</div>

---

## System Architecture

SEAGuard is architected as a distributed system with clear separation between the backend services, web dashboard, and mobile application.

<!-- Architecture Diagram -->
<div align="center">
  <img src="assets/architecture.png" alt="SEAGuard System Architecture" width="700"/>
  <br/>
  <em>Figure: SEAGuard System Architecture</em>
</div>

<br/>

| Component | Technologies | Role |
|---|---|---|
| **Backend API** | Node.js, Hono, PostgreSQL, Drizzle ORM | High-performance REST API handling data ingestion, AI prediction, authentication, and real-time monitoring |
| **AI Models** | LGBM (Light Gradient Boosting Machine) | Binary flood and landslide risk classification using data from GDACS, USGS, and ReliefWeb |
| **Web Frontend** | React 18, TypeScript, Vite, Tailwind CSS, TanStack Query, shadcn/ui | Interactive dashboard for risk visualization, alerts, and disaster education |
| **Mobile App** | React Native, Viro AR, Google Gemini 2.5 Flash, React Native Maps, Google Places API | Location-based emergency support with AR navigation and AI-powered guidance |

---

## Prototype

Try SEAGuard now:

| Platform | Link |
|---|---|
| **Web Dashboard** | [seaguard.netlify.app](https://seaguard.netlify.app/) |
| **Android APK** | [Download from Google Drive](https://drive.google.com/drive/folders/1mtSj_nQmXwJLVnQTn9R34xf5T2Km5tDt?usp=sharing) |

---

## Contributors

Built with dedication by **Team LabtekV** for Borneo Hackwknd.

<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/randy-verdian/"><img src="assets/team/randy.png" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Randy Verdian"/></a><br/>
      <strong><a href="https://www.linkedin.com/in/randy-verdian/">Randy Verdian</a></strong><br/>
      <em>Leader · Fullstack Developer</em>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/muhammad-althariq-fairuz-10503a247/"><img src="assets/team/althariq.png" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Muhammad Althariq Fairuz"/></a><br/>
      <strong><a href="https://www.linkedin.com/in/muhammad-althariq-fairuz-10503a247/">Muhammad Althariq Fairuz</a></strong><br/>
      <em>AI Engineer</em>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/oliviachristyl/"><img src="assets/team/olivia.png" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Olivia Christy Lismanto"/></a><br/>
      <strong><a href="https://www.linkedin.com/in/oliviachristyl/">Olivia Christy Lismanto</a></strong><br/>
      <em>Product Manager</em>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/saadabha/"><img src="assets/team/saad.png" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Saad Abdul Hakim"/></a><br/>
      <strong><a href="https://www.linkedin.com/in/saadabha/">Saad Abdul Hakim</a></strong><br/>
      <em>Fullstack Developer</em>
    </td>
    <td align="center">
      <a href="https://www.linkedin.com/in/shafiq-irvansyah/"><img src="assets/team/shafiq.png" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Shafiq Irvansyah"/></a><br/>
      <strong><a href="https://www.linkedin.com/in/shafiq-irvansyah/">Shafiq Irvansyah</a></strong><br/>
      <em>Fullstack Developer</em>
    </td>
  </tr>
</table>
</div>

---

<div align="center">
  <sub>Made with care for the communities of ASEAN &mdash; Team LabtekV &copy; 2026</sub>
</div>
