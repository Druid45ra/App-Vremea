# 🌦️ Aplicație Meteo (Open-Meteo API)

Aplicație web simplă și modernă pentru afișarea vremii curente și a prognozei pe 7 zile, construită în **HTML, TailwindCSS și JavaScript**.  
Datele meteo sunt preluate în timp real prin **[Open-Meteo API](https://open-meteo.com/)**, fără a fi nevoie de chei de autentificare.

---

## ✨ Funcționalități principale

- 🔍 **Căutare orașe** – introduci numele unui oraș și aplicația afișează vremea curentă.
- 📍 **Locația mea** – folosește geolocația browserului pentru a detecta poziția ta (funcționează doar pe HTTPS sau localhost).
- 🌡️ **Date meteo curente**:
  - Temperatură actuală și resimțită
  - Descrierea condițiilor meteo (senin, ploaie, ninsoare etc.)
  - Umiditate, vânt, presiune atmosferică
  - Răsărit și apus
- 📅 **Prognoză pe 7 zile** – temperaturi maxime/minime și iconițe sugestive pentru fiecare zi.
- ⭐ **Favorite** – poți salva orașele preferate în localStorage și le poți accesa rapid.
- 🕒 **Ora locală** – afișată în timp real pentru fiecare locație.

---

## 🛠️ Tehnologii folosite

- **HTML5** – structură semantică
- **TailwindCSS** – stilizare modernă și responsivă
- **JavaScript (ES6+)** – logica aplicației
- **Open-Meteo API**:
  - [Geocoding API](https://open-meteo.com/en/docs/geocoding-api) – pentru coordonatele orașelor
  - [Forecast API](https://open-meteo.com/en/docs) – pentru datele meteo curente și prognoză

---

## 🚀 Instalare și rulare

1. Clonează repository‑ul:
   ```bash
   git clone https://github.com/Druid45ra/App-Vremea.git
   cd App-Vremea


2. Deschide fișierul index.html în browser. ⚠️ Pentru funcția Locația mea, trebuie să rulezi aplicația pe localhost sau pe un server HTTPS.

Exemple:

Cu Python:

bash
python -m http.server
apoi accesează http://localhost:8000

Cu Node.js:

bash
npx serve
apoi accesează http://localhost:3000
