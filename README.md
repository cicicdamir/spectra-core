# 🛰️ SPECTRA-CORE

**Spectra-Core** is a high-fidelity visual data encoding and decoding engine. It transforms raw text streams into high-density chromatic matrices (images), utilizing deterministic color distribution for maximum data integrity.

---

## 🛠️ Technical Specifications

The project implements specific algorithms to ensure data persistence and readability even through optical scanning:

* **Core Engine**: Spectra-V25 (Stable)
* **Grid Density**: 130x90 pixels (11,700 total data points)
* **Color Logic**: Golden Angle (137.5°) distribution in HSL space to ensure maximum contrast between individual characters.
* **Recovery Algorithm**: 9-point kernel sampling designed to neutralize noise caused by anti-aliasing or image compression.

## 🚀 Live Demo

You can run the engine directly in your browser without any installation:
👉 **[LIVE DEMO - ACCESS ENGINE](https://cicicdamir.github.io/spectra-core/)**

---

## 📖 Operational Guide

### Encoding (Text to Image)
1. Input your desired string into the **Data Stream** terminal.
2. Click **Compile Matrix** to generate the visual representation.
3. Download the resulting `.png` file via the **Export** button.

### Decoding (Image to Text)
1. Click **Restore** (or Load Matrix) and select a previously generated Spectra image.
2. The engine will automatically initiate a scan of the matrix.
3. The decoded payload will appear in the **Signal Recovered** modal.

---

## 🧪 Sample Data

A sample file named `SPECTRA_V20_DATA.png` is included in this repository. You can use it to test the recovery function:
1. Download the sample image.
2. Upload it to the Spectra-Core live application.
3. Verify the output "payload" matches the original signal.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to fork, modify, and distribute for both private and commercial use.

---
**Developed by [cicicdamir](https://github.com/cicicdamir)** // 2026

