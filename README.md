🚦 Safer Route
AI-Powered Blackspot Analyzer for Safer Navigation

📌 Overview
Safer Route is a Streamlit-based application that compares the fastest route with the safest route between two locations.
It uses accident blackspot clustering data to highlight danger zones and helps users make informed travel decisions.

✨ Features
- 🗺️ Interactive Map (Folium + Leaflet + CARTO)
- 🚗 Fastest Route (red dashed line)
- 🛡️ Safest Route (green solid line, avoids blackspots)
- 🔴 Accident Blackspots shown with risk zones (High, Medium, Low)
- 📊 Safety Report with score (Safe / Moderate Risk / High Risk)
- ⚖️ Route Comparison Table (distance, time, safety score, events)
- 🤖 AI Recommendation suggesting whether to take fastest or safest route

🛠️ Tech Stack
- Python (core logic)
- Streamlit (web app interface)
- Folium + Leaflet + CARTO (map visualization)
- NumPy / Pandas (data handling)
- Haversine Formula (distance calculation)


📊 Example Output
- Fastest Route: 12.5 km, 30 min, Safety Score 50/100 (Moderate Risk)
- Safest Route: 14.0 km, 35 min, Safety Score 95/100 (Safe)
- Recommendation: Take the safest route — avoids 3 danger zones and 39,478 events.

👩‍💻 Contributors
- Sneha & Shreya @ 2025
