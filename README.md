# ML Based Cyber Threat Detection and Visualization Dashboard

##  Project Overview
This project proposes a **Machine Learning (ML) framework** for improving network security by detecting and visualizing cyber threats in real time.  
Traditional IDS tools struggle with zero-day attacks and generate excessive false alarms. Our solution integrates:

- 🔍 **ML Detection Engine** → Classifies network traffic as normal or malicious  
- 📊 **Interactive Visualization Dashboard** → Provides actionable intelligence with real-time insights  

---

##  Objectives
- Achieve **>98% detection accuracy** with **<1% False Positive Rate (FPR)**  
- Build a **Random Forest model** for multi-class attack classification  
- Provide a **dashboard** showing:
  - Attack distribution  
  - Threat intensity  
  - Temporal analysis  

---

##  Methodology
- **Dataset**: CICIDS 2017 (modern, labeled attack types)  
- **Models**: Random Forest (supervised) + Isolation Forest (unsupervised anomaly detection)  
- **Pipeline**:
  1. Data ingestion & preprocessing  
  2. ML classification (Normal vs Threat)  
  3. Alert storage & severity scoring  
  4. Dashboard visualization (Plotly Dash / Streamlit)  

---

##  Project Timeline
| Phase | Description | Duration |
|-------|-------------|----------|
| I     | Data Preparation & Literature Review | 4 Weeks |
| II    | ML Model Training & Optimization | 6 Weeks |
| III   | Dashboard Development & Integration | 5 Weeks |
| IV    | Testing, Evaluation & Documentation | 3 Weeks |

---

##  Expected Outcomes
- Robust ML threat detection model  
- Functional visualization dashboard  
- Faster analyst response compared to manual log analysis  

---

##  Ethical Considerations
- Only public datasets (CICIDS 2017) used  
- No personal data involved  
- Models designed for defensive, responsible use  

---

##  Repository Contents
- `proposal.pdf` → Semester project proposal document  
- `README.md` → Project overview and instructions  

---

##  Author
**Ezzah Tahir**  
BS Information Technology, International Islamic University Islamabad  
