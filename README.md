# 🖥️ Digital Twin Lighting Study – Office Environment


## 🎥 Demo
<p align="center">
  <img src="media/digital_twin_and_lighting.gif" width="900"/>
</p>

---

## 📸 Highlights

<p align="center">
  <img src="images/digital_twin_lighting_01.png" width="700"/>
</p>

<p align="center">
  <img src="images/digital_twin_lighting_02.png" width="700"/>
</p>

<p align="center">
  <img src="images/digital_twin_lighting_03.png" width="700"/>
</p>

<p align="center">
  <img src="images/digital_twin_lighting_04.png" width="700"/>
</p>

---

## 🧠 Project Overview

This project demonstrates the creation of a **real-time digital twin environment** using NVIDIA Omniverse and OpenUSD, with a strong emphasis on **lighting, material realism, and scene composition**.

The scene represents a modern office workspace, designed to explore how **practical lighting setups** (lamps, monitors, and daylight) influence realism and visual storytelling in a digital twin context.

---

## 🎯 Key Objectives

- Build a structured OpenUSD scene using proper hierarchy and referencing
- Develop physically plausible lighting using multiple light sources:
  - Area lighting (RectLight for window simulation)
  - Practical lighting (lamp as primary focal source)
  - Fill lighting (monitor glow simulation via SphereLight)
- Achieve cinematic composition using:
  - Contrast (warm vs cool lighting)
  - Shadow shaping
  - Reflection and material response
- Optimize scene for real-time rendering in Omniverse

---

## ⚙️ Technical Breakdown

### 🧱 Scene Construction
- OpenUSD stage composition with modular asset organization
- Version-controlled USD stages (`v01 → v03`)
- Clean separation of:
  - `/assets`
  - `/materials`
  - `/usd`
  - `/media`

---

### 💡 Lighting Strategy

| Light Source | Purpose |
|------|--------|
| RectLight (Window) | Simulated daylight entry |
| SphereLight (Monitors) | Fake emissive screen glow |
| DiscLight | Directional sunlight shaping |
| Practical Lamp | Primary cinematic focal point |

---

### 🎨 Materials

- OmniPBR-based materials for:
  - Wood (desk surface)
  - Matte walls
  - Metallic lamp structure
- Reflection tuning for realism (desk surface highlights)
- Color variation for wall art to avoid flat composition

---

### 🎥 Camera & Composition

- Multiple cinematic camera angles captured
- Depth and framing used to guide viewer focus
- Final hero shot emphasizes:
  - Shadow interplay
  - Warm lighting contrast
  - Surface reflections

---

## 🚀 Why This Matters

This project demonstrates key digital twin engineering skills:

- Scene assembly using OpenUSD
- Real-time lighting design in Omniverse
- Visual storytelling through simulation environments
- Understanding of physically-inspired rendering techniques

---

## 📁 Project Structure

project_06_digital_twin_desk/
├── assets/
├── images/
├── materials/
├── media/
│ └── digital_twin_and_lighting.gif
├── references/
├── usd/
│ ├── desk_twin_v01.usda
│ ├── desk_twin_v02.usda
│ └── desk_twin_v03.usda


---

## 🔮 Next Steps

- Introduce sensor simulation (camera / LiDAR)
- Expand into synthetic data generation pipeline
- Add semantic labeling for AI training workflows

---
