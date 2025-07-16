# BTC Price Prediction

Time‑series forecasting for Bitcoin price using a Jupyter Notebook, with helper scripts and reproducible environment.

---

## 📋 Contents

- **notebooks/**  
  - `BTCprediction.ipynb` — Ana çalışma dosyası  
- **src/**  
  - `utils.py` — Veri işleme ve model fonksiyonları (yardımcı modüller)  
- **data/**  
  - Ham veri dosyaları (`*.csv`, `*.json`)  
- **outputs/**  
  - Üretilen grafikler, model objeleri, sonuç CSV’leri  
- `.gitignore`  
- `requirements.txt`  
- `README.md`  

---

## 🛠️ Requirements

```bash
# Sanal ortam oluştur ve aktif et
python3 -m venv venv
source venv/bin/activate

# Gerekli paketler
pip install -r requirements.txt
