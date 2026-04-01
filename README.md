# 🌕 Artemis II Launch Tracker  
A clean, real‑time mission dashboard built to visualize the Artemis II launch timeline, crew details, mission milestones, and a simulated distance‑from‑Earth model — all wrapped in a responsive, modern UI.  
Live site: **`https://valerioc1-commits.github.io/artemis-ii-tracker/` [(valerioc1-commits.github.io in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fvalerioc1-commits.github.io%2Fartemis-ii-tracker%2F")**

---

## 🚀 Overview  
This project is a standalone HTML/CSS/JS page designed to track the Artemis II mission in a visually engaging way. It includes:

- A live countdown to the scheduled launch time  
- A dynamic mission status bar  
- A detailed launch‑day timeline with automatic progression  
- A distance‑from‑Earth simulation based on the mission profile  
- Crew profiles for all four Artemis II astronauts  
- Embedded NASA livestream coverage  
- Full light/dark mode support  
- Responsive layout for desktop and mobile  

Everything runs client‑side — no frameworks, no backend, no external dependencies beyond the YouTube embed.

---

## 🛰 Features  

### **⏱ Real‑time Countdown**  
Automatically updates every second until launch, then switches to T+ mission time.

### **📡 Mission Status Logic**  
The status bar reflects fueling, terminal countdown, and post‑liftoff phases.

### **📘 Launch Timeline**  
Each milestone updates automatically based on real timestamps defined in JavaScript.

### **🌌 Distance Simulation**  
A custom model estimates distance and speed across six mission phases:
- Ascent  
- Orbit insertion  
- High Earth orbit  
- Lunar transit  
- Distant retrograde trajectory  
- Return to Earth  

### **👩‍🚀 Crew Profiles**  
Includes all four Artemis II crew members with color‑coded avatars.

### **🎥 NASA Livestream Embed**  
Direct YouTube embed of NASA’s official coverage.

---

## 🧩 File Structure  
```
/artemis-ii-tracker
│
├── index.html        # Main project file
└── README.md         # Project documentation
```

---

## 🌐 Deployment  
This project is deployed using **GitHub Pages**.

To view the live site:  
`https://valerioc1-commits.github.io/artemis-ii-tracker/` [(valerioc1-commits.github.io in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fvalerioc1-commits.github.io%2Fartemis-ii-tracker%2F")

To run locally, simply open the HTML file in a browser or serve it via a local web server for full iframe compatibility.

---

## 🛠 Technologies Used  
- **HTML5**  
- **CSS3** (custom design system + dark mode)  
- **Vanilla JavaScript** (timers, mission logic, distance model)  
- **GitHub Pages** for hosting  

---

## 📄 License  
This project is open for educational and personal use.  
NASA imagery and mission data belong to NASA and are used under public domain guidelines.

---

## ⭐ Future Enhancements  
Potential next steps include:

- Adding real telemetry when available  
- A multi‑page mission dashboard  
- A persistent mission log  
- Interactive 3D trajectory visualization  
- A mobile‑optimized control panel layout  

---

