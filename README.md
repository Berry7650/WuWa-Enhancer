# 🌊 Wuthering Waves Mobile Optimization (Snapdragon 732G)

Custom Unreal Engine 4 config files to improve **performance and stability** when running **Wuthering Waves (2024)** on mid-range Android devices — specifically for the **Snapdragon 732G / Adreno 618 GPU** (e.g., Moto G40 Fusion).

---

## 🎮 Game Overview

**Wuthering Waves** is a high-fidelity action RPG featuring:
- Fast-paced, combo-heavy combat
- Open-world traversal and verticality
- Dynamic weather and lighting
- Stylized anime visuals with real-time rendering

---

## 🔧 Optimization Goals

- 🚀 Smooth combat performance (30–60 FPS)
- 🔋 Reduced thermal throttling and power draw
- 🖼️ Maintain visual sharpness with upscaling
- 🔄 Balance between aesthetics and efficiency

---

## 📱 Target Hardware

|  Test Device            | Chipset          | GPU        |
|------------------|------------------|------------|
| Moto G40 Fusion  | Snapdragon 732G  | Adreno 618 |

---

## ⚙️ What's Included

- **`DeviceProfiles.ini`**
  - Adreno 618-specific tuning
  - Enables dynamic resolution and disables costly visual features

- **`Engine.ini`**
  - Reduces post-processing
  - Enables async rendering and efficient LOD scaling
  - Includes AMD FSR 1.0 sharpening

---

## 🧪 Performance Estimate (Moto G40 Fusion)

| Situation                | Estimated FPS |
|--------------------------|----------------|
| Exploration / dialogue   | 40–60 FPS       |
| Combat (normal)          | 35–45 FPS       |
| Combat (high FX/heavy)   | 25–35 FPS       |

> Performance is measured with `r.MobileContentScaleFactor=0.7` + FidelityFX FSR.

---

## 🗂️ Setup Instructions

1. Copy both `.ini` files into your ANDROID > DATA > COM.KUROGAME.WUTHERINGWAY... > FILES > UE4GAME > CLIENT > CLIENT > SAVED > CONFIG > ANDROID
