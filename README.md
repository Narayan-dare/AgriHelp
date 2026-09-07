# AgriHelp Mini / அக்ரிஹெல்ப் மினி 🌾🚜

**AgriHelp Mini** is a modern, responsive, and bilingual (English / Tamil) precision farm advisory dashboard engineered for South Indian farmers, agronomists, and agricultural researchers. It combines real-time micro-climate simulation, an intelligent **Soil Report Adder & Scientific Analyzer**, growth-stage phenology monitoring, and weather-triggered field action checklists.

---

## 🌟 Key Features / முக்கிய சிறப்பம்சங்கள்

- 🌐 **Full Bilingual Support (English / தமிழ்)**: Complete interface and recommendations presented with prominent English headings and refined Tamil subtitles.
- 🌾 **South Indian Cultivars Supported**:
  - **Rice (நெல்)** - *Oryza sativa*
  - **Cotton (பருத்தி)** - *Gossypium*
  - **Sugarcane (கரும்பு)** - *Saccharum officinarum*
  - **Ragi / Finger Millet (கேழ்வரகு)**
  - **Coconut Palm (தென்னை)**
  - **Groundnut (நிலக்கடலை)**
- 🧪 **Soil Report Adder & Scientific Lab Analyzer**:
  - **File Upload & Text Parser**: Drag-and-drop or paste raw Soil Health Card / TNAU lab test readings.
  - **1-Click Regional Presets**: Load official test profiles for *Delta Alluvial Soil*, *Coimbatore Black Cotton Soil*, *Madurai Red Loamy Soil*, or *Coastal Saline Soil*.
  - **Dynamic Agronomic Prescription**: Calculates exact dosages of **Urea (46% N)**, **DAP / SSP**, and **MOP (Potash)** in kg/acre and standard bags.
  - **Biofertilizer & Reclamation Protocol**: Organic carbon enrichment (FYM/Vermicompost), bio-inoculants (*Azospirillum*, *Phosphobacteria*), and lime/gypsum soil amendments.
  - **Printable Soil Health Card**: Format-ready printable view for field records.
  - **Report History**: Persistent local storage of tested plots.
- 🌡️ **Interactive Climate Simulator**: Real-time sliders for temperature (°C), soil moisture (%), air humidity (%), and soil pH.
- 🚨 **Multi-Tier Advisory Engine**:
  - Extreme Heat Stress Alerts (> 35°C–38°C)
  - Critical Moisture Deficit / Waterlogging Warnings
  - Fungal Disease & Pest Outbreak Indicators (Blast, Whitefly, Red rot)
- 📊 **Dynamic Analytics Chart**: Interactive Chart.js dual-axis monitoring curve showing simulated climate vs crop physiological thresholds.
- 📋 **Weather-Aware Field Tasks**: Daily checklist with automatic suggestions based on active weather simulations.
- 🌓 **Day / Dark Mode**: Fluid theme toggle with modern glassmorphism aesthetics.

---

## 🚀 Getting Started / தொடங்குவது எப்படி

### Prerequisites
No build steps or complex framework installations needed! All you need is a modern web browser and Python (or any static HTTP server).

### Quick Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Narayan-dare/AgriHelp.git
   cd AgriHelp
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
AgriHelp/
├── index.html       # Single-page application containing HTML5, Tailwind CSS, & dynamic JS rules
├── README.md        # Comprehensive documentation (Bilingual)
└── .gitignore       # Git ignore file
```

---

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript**: High performance, zero build dependencies.
- **Tailwind CSS**: Modern utility-first responsive styling with dark mode.
- **Plus Jakarta Sans**: High-legibility modern typography.
- **FontAwesome 6**: Scalable vector icons.
- **Chart.js**: Dynamic real-time agricultural analytics visualizations.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
