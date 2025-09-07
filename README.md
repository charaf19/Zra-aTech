
# 🌾 ZraïaTech

**Smart Agriculture for Morocco**  
ZraïaTech is an innovative platform that combines **satellite imagery**, **lightweight micro-trials**, and **AI-driven recommendations** to help agronomists and farmers make better, data-powered decisions.  

Our goal is to **optimize demonstration plots, improve fertilization strategies, and deliver simple, localized advisories** that boost productivity and sustainability in Moroccan agriculture.

---

## ✨ Key Features

- 📡 **Remote Sensing**
- 🧪 **Micro-Trial Designer**
- 🤖 **Adaptive AI**
- 💬 **Advisory Generator**
- 📊 **Interactive Dashboard**

---

## 🚀 Mission

Empower Moroccan farmers and organizations with **data-driven, sustainable solutions** that:  
- Increase cereal yields and resilience.  
- Reduce field workload through remote sensing & automation.  
- Strengthen farmer trust with clear, expert-validated advisories.  

---

## 🛠 Tech Stack

- **Remote Sensing & ML**: Python, Rasterio, Xarray, GDAL, GeoPandas, LightGBM/XGBoost, PyTorch.  
- **Backend Services**: FastAPI, Docker, PostgreSQL/PostGIS, MinIO/S3.  
- **Frontend**: React/Next.js, MapLibre/Leaflet, Plotly.  
- **Messaging**: WhatsApp Cloud API, SMS integration.  
- **Infra**: Dockerized microservices, CI/CD, small VPS/VM deployment.  

---

## 📂 Repository Structure

```bash
ZraiaTech/
├── data/              # Sample datasets & boundaries
├── notebooks/         # Exploration & RS preprocessing
├── src/
│   ├── ingestion/     # RS & weather data pipelines
│   ├── services/      # Targeting, trial design, learning, advisory
│   ├── dashboard/     # Frontend (React/Next.js)
│   └── utils/         # Common helpers
├── docs/              # Documentation & diagrams
└── README.md
````

---

## 📖 Getting Started

### Prerequisites

* Python 3.9+
* Node.js 18+ (for dashboard)
* Docker (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-org>/ZraiaTech.git
cd ZraiaTech

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install backend dependencies
pip install -r requirements.txt

# Run dashboard
cd src/dashboard
npm install
npm run dev
```

---

## 📊 Usage

1. Define your **pilot crop & area** (e.g. wheat in Settat–Benguerir).
2. Use the **trial designer** to generate field layouts.
3. Monitor vegetation indices via the **dashboard**.
4. Generate **localized advisories** for farmers (FR/EN/Arabic).

---

## 🧭 Roadmap

* [x] Phase 1: MVP (wheat, 1 province, RS-based monitoring, WhatsApp advisories).
* [ ] Phase 2: Expand to olives/citrus and multiple provinces.
* [ ] Soil-lab data integration & irrigation scheduling.
* [ ] Edge inference & mobile offline tools for agronomists.

---

## 🤝 Partners & Collaboration

* **OCP Group — Programme Al Moutmir**
* **UM6P (CRSA & experimentation farm)**
* **APNI (scientific advisory, optional)**

We welcome new collaborators in **precision agriculture, AI, and sustainable farming**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍👩‍👧‍👦 Team

* **Precision Ag / Remote Sensing** → RS pipelines & trial design.
* **Data Scientist** → Contextual bandit & advisory LM.
* **AI Software Engineer** → Backend services & CI/CD.
* **Frontend Engineer** → Dashboard development.
* **Biz Dev** → Partner relations & farmer engagement.

---

## 🌍 Impact

By combining **technology, science, and local expertise**, ZraïaTech contributes to:

* Stronger food security in Morocco.
* Sustainable resource use in agriculture.
* Empowered farmers and resilient rural ecosystems.

---



