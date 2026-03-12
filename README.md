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
  <img src="../.github/assets/preview-web.png" alt="SEAGuard Web Dashboard" width="700"/>
  <br/>
  <em>SEAGuard Web Dashboard &amp; Mobile App</em>
</div>

<br/>

### Web Platform

An interactive dashboard designed for regional situational awareness and institutional use.

**Real-Time Disaster Monitoring**
| Feature | Description |
|---|---|
| **Active Zones Map** | Interactive visualization of disaster zones categorized as Evacuation, Caution, and Danger |
| **Global & Local Alerts** | Real-time push notifications and alerts for ongoing and incoming hazards |
| **Risk Forecasts** | Data-driven predictions for upcoming environmental risks across the ASEAN region |

**Emergency Resources**
| Feature | Description |
|---|---|
| **Global Emergency Contacts** | Quick access to maritime and local emergency services across all ASEAN countries |
| **AI Chatbot Assistant** | 24/7 intelligent assistant for safety queries and emergency guidance |
| **Survival Guides** | Comprehensive, disaster-specific survival instructions available offline |

**Localization & Accessibility**
| Feature | Description |
|---|---|
| **Multi-language Support** | Fully localized in English, Bahasa Indonesia, Filipino, Thai, Vietnamese, Malay, Burmese, Khmer, and Lao |
| **Personalized Setup** | Personalized experience based on the user's location and preferred language |

### Mobile App

A location-aware companion app for on-the-ground emergency support.

**Smart Evacuation**
| Feature | Description |
|---|---|
| **Nearest Safe Zones** | Automatically detects and suggests the closest hospitals, shelters, and assembly points |
| **AR-Guided Navigation** | Immersive AR navigation paths (Viro AR) to guide users to safety in real-time |

**Disaster Simulator**
| Feature | Description |
|---|---|
| **AR Simulator** | Immersive AR experience to visualize disaster scenarios in a safe environment |
| **AI Voice Guide** | Interactive real-time assistant powered by Gemini AI providing step-by-step survival guidance |
| **Quiz Gamification** | Interactive quizzes to test and reinforce disaster preparedness knowledge |

**Community Reports**
| Feature | Description |
|---|---|
| **Crowdsourced Safety** | Real-time localized feeds of disasters reported by nearby users |
| **AI Hazard Scanner** | Snap a photo and let AI automatically detect hazard level and water depth for accurate reporting |

**Multilingual Support**
| Feature | Description |
|---|---|
| **All ASEAN Languages** | Fully localized in Indonesian, Thai, Vietnamese, Malay, Filipino, Khmer, Lao, and more — so no community is left behind |

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
      <img src="assets/team/randy.jpg" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Randy Verdian"/><br/>
      <strong>Randy Verdian</strong><br/>
      <em>Team Leader</em>
    </td>
    <td align="center">
      <img src="assets/team/althariq.jpg" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Muhammad Althariq Fairuz"/><br/>
      <strong>Muhammad Althariq Fairuz</strong><br/>
      <em>Member</em>
    </td>
    <td align="center">
      <img src="assets/team/olivia.jpg" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Olivia Christy Lismanto"/><br/>
      <strong>Olivia Christy Lismanto</strong><br/>
      <em>Member</em>
    </td>
    <td align="center">
      <img src="assets/team/saad.jpg" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Saad Abdul Hakim"/><br/>
      <strong>Saad Abdul Hakim</strong><br/>
      <em>Member</em>
    </td>
    <td align="center">
      <img src="assets/team/shafiq.jpg" width="100" height="100" style="border-radius:50%; object-fit:cover;" alt="Shafiq Irvansyah"/><br/>
      <strong>Shafiq Irvansyah</strong><br/>
      <em>Member</em>
    </td>
  </tr>
</table>
</div>

---

<div align="center">
  <sub>Made with care for the communities of ASEAN &mdash; Team LabtekV &copy; 2025</sub>
</div>
