# 🎧 Puerto Morelos Underwater Sound Catalog

This repository hosts an interactive standalone catalog of underwater sounds recorded in the **Puerto Morelos Reef National Park (Mexican Caribbean)**.

Each sound entry includes:
- Audio playback controls  
- Spectrogram visualization  
- Acoustic parameters: frequency range, duration, and signal-to-noise ratio (SNR)

The catalog supports research on **passive acoustic monitoring**, **fish vocalization**, and **coral reef soundscapes**, allowing users to explore representative sound events and listen to short clips extracted from field recordings.

---

## 📂 Repository Structure

```
index.html                → main interactive catalog (ready for GitHub Pages)
data.js                   → metadata with sound information
clips/                    → short underwater sound clips (.wav)
spectrograms/             → spectrogram images (.png)
```

---

## 🌐 View Online

Once GitHub Pages is enabled, visit:  
👉 [https://alejora2402.github.io/Puerto_Morelos_Underwater_Sound_Catalog/](https://alejora2402.github.io/Puerto_Morelos_Underwater_Sound_Catalog/)

---

## ⚙️ Local Preview

If you want to test locally before publishing:

```bash
python -m http.server
```

Then open in your browser:  
[http://localhost:8000](http://localhost:8000)

---

### 🪸 Author
**Alejandro Ramos**  
Researcher in Physical Oceanography and Underwater Acoustics  
[sono-calli.com](https://www.sono-calli.com)
