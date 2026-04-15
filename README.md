<!-- HEADER ANIMATION -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:2575fc&height=200&section=header&text=Image%20Captioning%20Project&fontSize=40&fontColor=ffffff&animation=fadeIn" />
</p>

<h1 align="center">🧠 Image Captioning using Deep Learning</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=F700FF&size=25&center=true&vCenter=true&width=600&lines=Deep+Learning+Project;CNN+%2B+LSTM+%2B+Transformers;Automatic+Image+Caption+Generator;Built+with+Love+%F0%9F%92%9C" />
</p>

---

## 🎥 Demo (GIF)

<p align="center">
  <img src="PUT_YOUR_GIF_HERE.gif" width="600"/>
</p>

> ✨ Example: Upload image → Model generates caption automatically

---

## 🚀 Project Overview

This project builds an **end-to-end Image Captioning system** that:
- 🖼️ Extracts features from images using CNN models
- 🧠 Generates captions using sequence models
- 🔁 Compares multiple architectures for best performance
- 🎨 Provides a simple GUI for user interaction
- 🌐 Uses scraping to build custom dataset

---

## 🧠 Models Used

<div align="center">

| Model | Type | Purpose |
|------|------|--------|
| 🧩 LSTM | Sequence Model | Generate captions |
| 🧠 Transformer | Attention Model | Advanced captioning |
| 🖼️ VGG16 | CNN | Feature extraction |
| 🔍 ResNet50 | CNN | Deep feature extraction |
| ⚡ EfficientNetB0 | CNN | Optimized performance |

</div>

---

## ⚙️ Pipeline

```mermaid
graph LR
A[Image] --> B[CNN Feature Extraction]
B --> C[Feature Vector]
C --> D[LSTM / Transformer]
D --> E[Generated Caption]
