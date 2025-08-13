# Tips Dashboard — Streamlit App

An interactive data visualization dashboard built with **Streamlit** to explore the classic **Tips** dataset.  
The app provides filters, charts, and quick insights in a clean, responsive UI.

---

## 📊 Features
- **Interactive Filters:** Filter by gender, day, time, and smoker status.
- **Dynamic Charts:** Visualizations using **Matplotlib** and **Seaborn**.
- **Key Metrics:** Summary stats (averages, counts, distributions) computed on-the-fly.
- **Lightweight & Fast:** Runs locally or on **Streamlit Cloud**.

---

## 📂 Project Structure
```
Tips-Dashboard/
├── tips-dashboard.py        # Main Streamlit app
├── requirements.txt         # Python dependencies
├── Data/
│   └── tips.csv             # Dataset file (required)
├── Images/                  # Optional screenshots for README
│   ├── bar_chart.png
│   ├── scatter_plot.png
│   └── box_plot.png
└── README.md
```

> **Note:** Folder names are **case-sensitive** on the server. Keep `Data/` and `Images/` exactly as written.

---

## ⚙️ Installation (Local)
1) Clone the repository:
```bash
git clone https://github.com/AdhamEssam7/Tips-Dashboard.git
cd Tips-Dashboard
```
2) Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ▶️ Run Locally
```bash
streamlit run tips-dashboard.py
```
Then open the local URL shown in the terminal (usually `http://localhost:8501`).

---

## 🚀 Deploy on Streamlit Cloud
1. Push this project to GitHub (see repo link above).
2. Go to **https://share.streamlit.io/** and sign in with GitHub.
3. Click **New app** → select repo `AdhamEssam7/Tips-Dashboard`.
4. Branch: `main`  
   Main file path: `tips-dashboard.py`
5. Click **Deploy**. Your app will build and get a public URL.

> After deployment, update the live link below 👇

**Live Demo:** _add the URL here after deploy_

---

## 📘 Data
- The app expects the dataset at: `Data/tips.csv`
- If you change the location/name, update the path in `tips-dashboard.py` accordingly.
- For Windows paths in code, prefer forward slashes: `Data/tips.csv` (not `Data\tips.csv`).

---

## 📷 Screenshots (optional)
Add images under `Images/` and reference them here:
![Bar Chart](Images/bar_chart.png)
![Scatter Plot](Images/scatter_plot.png)
![Box Plot](Images/box_plot.png)

---

## 📝 License
MIT (feel free to use and modify).

**Author:** Adham Essam
