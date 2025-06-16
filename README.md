# 🏥 Nearby Healthcare Finder Web App

This project is a lightweight web application that allows users to find nearby healthcare facilities using geolocation and OpenStreetMap (via Overpass API). It leverages **Leaflet.js** for mapping and **Tailwind CSS** for UI styling.

---

## 📋 Table of Contents

* [Features](#-features)
* [Demo](#-demo)
* [Technologies Used](#-technologies-used)
* [Installation](#-installation)
* [Usage](#-usage)
* [How It Works](#-how-it-works)
* [License](#-license)

---

## ✨ Features

* 📍 Real-time user location detection
* 🏥 Select facility types: Hospital, Dentist, Physiotherapist, Clinic, Pharmacy
* 🌍 View results on an interactive map
* 📄 Display details like name, address, phone, and distance
* 🖼 Placeholder images for each result

---
## 🛠 Technologies Used

* **HTML5** + **CSS3** + **JavaScript (ES6)**
* **Leaflet.js** – Map rendering
* **Tailwind CSS** – UI styling
* **OpenStreetMap + Overpass API** – Data source for facilities

---

## 🧰 Installation

1. Clone this repository:

```bash
git clone https://github.com/hemanthh35/SmartHealth_Mapper.git)
cd nearby-healthcare-map
```

2. Open `index.html` in a web browser:

```bash
open index.html  # Or just double-click on it
```

> No additional backend or build steps required.

---

## ▶️ Usage

1. Allow location permission in your browser.
2. Select a healthcare facility type from the dropdown.
3. Click **"Find Nearby"**.
4. The app fetches nearby facilities and shows them on the map.

---

## 🧠 How It Works

* Uses `navigator.geolocation` to detect user's location.
* Sends a dynamic Overpass QL query to the OpenStreetMap Overpass API.
* Maps the results with Leaflet and displays them in a list and on the map.
* Calculates distance using the Haversine formula.

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to fork, modify, and use for your own healthcare apps or mapping experiments!

---
