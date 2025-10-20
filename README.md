# UW Transit 🚍

UW Transit is a fullstack web app designed to help students navigate and move safely around the University of Washington campus. The app shows live crowd density data, allowing users to spot busy areas and report crowded or unsafe zones in real time.

---

## 🚀 Tech Stack
- **Frontend:** React (Vite) + TailwindCSS  
- **Backend:** Python (Flask)  
- **Database:** SQLite  
- **Hosting:** Render (Frontend + Backend)  
- **Maps:** Google Maps JavaScript API + HeatmapLayer  

---

## 🗺️ Features
- Interactive map showing live crowd heatmap  
- Report crowded or dangerous areas instantly  
- View confirmed crowd and danger zones from the backend  
- Dynamic UI with marker placement and confirmation  

---

## ⚙️ Deployment (Render)

### **Frontend (Static Site)**
- **Root Directory:** `frontend`  
- **Build Command:** `npm install && npm run build`  
- **Publish Directory:** `dist`  

### **Backend (Web Service)**
- **Root Directory:** `backend`  
- **Build Command:** `pip install -r requirements.txt`  
- **Start Command:**  
  ```bash
  python main.py
