# AgriHelp Mini / அக்ரிஹெல்ப் மினி 🌾🚜

**AgriHelp Mini** is a modern, responsive, and bilingual (English / Tamil) precision farm advisory dashboard engineered for South Indian farmers and agricultural researchers. It combines micro-climate simulation, soil lab report diagnostics (NPK & pH), and growth-stage-specific agronomic rules to deliver real-time corrective actions and pest/disease warnings.

---

## 🌟 Key Features / முக்கிய சிறப்பம்சங்கள்

- 🌐 **Full Bilingual Support (English / தமிழ்)**: Complete interface and advisory recommendations presented with English primary and Tamil secondary translations.
- 🌾 **South Indian Crop Coverage**: Built-in agronomic profiles for:
  - **Rice (நெல்)** - *Oryza sativa*
  - **Cotton (பருத்தி)** - *Gossypium*
  - **Sugarcane (கரும்பு)** - *Saccharum officinarum*
  - **Ragi / Finger Millet (கேழ்வரகு)**
  - **Coconut Palm (தென்னை)**
  - **Groundnut (நிலக்கடலை)**
- 🌡️ **Interactive Climate Simulator**: Real-time sliders for temperature (°C), soil moisture (%), air humidity (%), and soil pH to simulate micro-climates.
- 🧪 **Soil Lab NPK & pH Diagnostics**: Interactive soil test report analysis with automated fertilizer correction recommendations (Urea, SSP/DAP, MOP, Lime/Gypsum).
- 🚨 **Multi-Tier Advisory Engine**:
  - Global Heat Waves & Extreme Weather Alerts
  - Critical Crop Stress Warnings
  - Fungal Disease & Pest Outbreak Indicators (e.g., Whitefly, Blast)
- 📊 **Analytics & Stage Monitoring**: Real-time metrics, growth-stage transitions, and interactive soil composition graphs.
- 🌓 **Day / Dark Mode**: Fluid theme toggle with glassmorphism and modern UI aesthetics.

---

## 🚀 Getting Started / தொடங்குவது எப்படி

### Prerequisites
No complex framework dependencies required! All you need is a modern web browser and Python (or any static HTTP file server).

### Quick Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/agrihelp-mini.git
   cd agrihelp-mini
   ```

2. **Start the local HTTP server**:
   ```bash
   python -m http.server 8000
   ```

3. **Open in your browser**:
   Navigate to [http://localhost:8000](http://localhost:8000)

---

## 📁 Project Structure

```
agrihelp-mini/
├── index.html       # Single-page application containing HTML5, Tailwind CSS, & dynamic JS rules
├── README.md        # Documentation and guide (Bilingual)
└── .gitignore       # Git ignore file
```

---

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript**: High performance, zero build step required.
- **Tailwind CSS**: Modern utility-first responsive styling with dark mode support.
- **FontAwesome**: Scalable vector icons.
- **Chart.js**: Dynamic real-time agricultural analytics and soil radar/bar visualizations.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
