# GeoRecord SkyLedger

**A powerful, fully offline web app for daily monitoring and permanent archival of sky conditions, electromagnetic signals, microwave radiation, sunlight data, contracted spray operators, contaminant testing, and aircraft flight paths.**

Designed for citizen scientists, researchers, and individuals who need searchable, timestamped records suitable for insurance claims, legal documentation, regulatory complaints, and personal accountability.

> *"It would be good to have an app or database that mainstreams the information each day, the towers signal, the microwaving zones, hours of sunlight, monitor the skies, so there is a record that can be searched after these types of events for insurance and legal."*  
> — @avaleighfilm on X (May 2026)

---

## 🌟 Key Features

### 📊 **Dashboard**
- Real-time overview of today’s key metrics (sunlight hours, tower signal strength, microwave levels, contrail coverage)
- 30-day sunlight deviation trend chart
- Critical event alerts with one-click report generation

### 📝 **Daily Intake Log**
- Comprehensive form to record:
  - Sunlight (observed vs expected with automatic deviation %)
  - Tower signals (dBm, tower count, frequency bands)
  - Microwave radiation levels + zone descriptions
  - Sky observations (contrail %, number of spray aircraft, detailed notes)
  - Multiple photo uploads (stored locally)
- “Mainstream Today’s Data” one-click daily sync button

### 🗺️ **Sky Monitor**
- Interactive Leaflet map centered on your location
- Tower markers with signal strength popups
- Color-coded microwave radiation zones
- Animated suspected spray flight paths with live-moving aircraft icons
- “Scan Skies Now” button for real-time detection logging

### 📡 **Signals & Radiation**
- Detailed nearby tower list with live readings
- Active microwave zone monitoring and alerts

### 🔍 **Searchable Archive**
- Full historical database of all logged entries
- Powerful filters (keyword search, date range)
- Click any record to view full details + attached photos
- One-click CSV export for external analysis

### 🏢 **Contracted Operators**
- Pre-populated list of known cloud-seeding and geoengineering contractors
- Fully editable — add, view, or remove entries
- Includes company type, contracting entity, active regions, and status

### 🧪 **Contaminant Tests**
- Log lab results for air, soil, rainwater, etc.
- Track Aluminum, Barium, Strontium, and other contaminants
- Searchable history with lab source and notes

### ✈️ **Flight Path Tracker**
- Log suspected spray aircraft (callsign, type, route, altitude, activity)
- Visual integration with the Sky Monitor map
- Quick “Add Flight” button

### 📄 **Legal & Insurance Reports**
- Professional PDF report generation (full monthly or quick incident report)
- Includes all correlated data, timestamps, chain-of-custody, notes, and photos
- Ready for submission to insurance companies, attorneys, or government agencies

---

## 🚀 Getting Started

1. **Open the app**  
   Double-click `georecord.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

2. **Set your location** (optional but recommended)  
   Click the location bar at the top or use the **“Use My Location”** button for accurate map centering.

3. **Start logging**  
   Use the sidebar to navigate between sections.  
   Click **“MAINSTREAM TODAY’S DATA”** daily for quick simulated live updates, or fill out the **Daily Intake** form manually.

4. **Review & Export**  
   All data is automatically saved. Use the **Searchable Archive** or generate **PDF reports** anytime.

---

## 💾 Data Storage & Privacy

- **100% local** — everything is stored in your browser’s `localStorage`
- No data is sent to any server
- No account or login required
- Export anytime as CSV or PDF for backup/offline use
- Clear browser data to reset the app

---

## 🛠 Tech Stack

- Pure HTML5 + Tailwind CSS (via CDN)
- Leaflet.js (interactive maps)
- Chart.js (sunlight trend visualization)
- jsPDF (professional PDF report generation)
- Font Awesome icons
- Fully responsive and works offline after initial load

---

## 📜 Inspiration & Context

This application was created in direct response to the May 2026 X post by filmmaker @avaleighfilm, who called for a transparent, searchable daily record of geo-environmental phenomena for legal and insurance purposes following events such as the straight-line wildfire in the Florida Everglades.

The app provides exactly that capability in a professional, easy-to-use interface.

---

## ⚖️ Important Disclaimer

**GeoRecord is a citizen logging and archival tool only.**

- All data entered is user-generated or user-verified.
- This application does **not** constitute scientific proof, official measurement, or legal evidence.
- Always cross-reference with official sources (NOAA, EPA, FAA, state environmental agencies, accredited laboratories) before using any generated reports in formal proceedings.
- The creators make no claims regarding the scientific validity of any specific phenomenon logged by users.

Use responsibly and ethically.

---

## 📌 Future Ideas (Community Contributions Welcome)

- Integration with public APIs (Open-Meteo sunlight data, ADS-B flight tracking, OpenCelliD towers)
- Multi-user / shared ledger mode
- Mobile PWA support with offline camera capture
- Automated anomaly detection alerts
- Export to JSON for advanced analysis

---

## 📄 License

Free for personal, research, and non-commercial use.  
You may modify and redistribute with attribution.

---

**Built with care for transparency and accountability.**  
Thank you for using GeoRecord SkyLedger.

*Version 2.1 • May 2026*  
*Inspired by the vision of Ava Leigh Stewart (@avaleighfilm)*

---

**To run:** Simply open `georecord.html` in your browser. No installation required.
