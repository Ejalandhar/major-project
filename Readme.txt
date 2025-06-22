 Network Intrusion Detection System using Machine Learning
This project is a real-time Network Intrusion Detection System (NIDS) that uses machine learning to detect anomalies in network traffic. It helps identify unauthorized access, cyber-attacks, or unusual activity to enhance network security.
# 🚨 Network Intrusion Detection System using Machine Learning

A real-time **Network Intrusion Detection System (NIDS)** that uses machine learning to monitor and detect suspicious network activity. Built with **FastAPI** and **Streamlit**, this system provides smart detection, real-time visualization, and automated alerts to strengthen cybersecurity.

---

## 📌 Project Overview

This system analyzes live or uploaded network traffic, classifies packets using a trained ML model, and alerts the user or administrator when anomalies are detected. It combines automation, AI, and user-friendly design to offer a complete cybersecurity monitoring tool.

---

## ⚙️ How It Works

1. 🧑‍💻 **User Inputs** packet data via a web UI.
2. 🧮 **Features Extracted** from network data (e.g., IP, port, protocol).
3. 🤖 **ML Model** (trained on NSL-KDD dataset) predicts: _Normal_ or _Anomalous_.
4. 🚨 **Alerts Triggered** and logs are generated.
5. 📊 **Dashboard Updates** in real-time with visual insights and chatbot support.

---

## 🧠 Key Features

- ✅ Real-time packet analysis with **92%+ accuracy**
- 🔐 Secure login system
- 📩 Email alerts on detection
- 📁 CSV logging of all results
- 📈 Interactive **Streamlit dashboard**
- 💬 Built-in **AI chatbot** for cybersecurity help
- 📊 Dynamic bar/pie charts for traffic visualization

---

## 🛠 Tech Stack

| Layer      | Technology Used          |
|------------|---------------------------|
| Backend    | Python, FastAPI           |
| Frontend   | Streamlit                 |
| ML Model   | Isolation Forest, NSL-KDD |
| Data Flow  | Scapy, Pandas             |
| Alerts     | SMTP (Email)              |
| Visualization | Matplotlib, Plotly     |

---

## 🎯 Benefits

- 🔍 **Detects zero-day and unknown attacks**
- 🧠 **Learning-based model** improves with more data
- 🧑‍🎓 **Easy to use** even for non-technical users
- ⏱ **Automated alerts** reduce monitoring effort
- 💬 **Chatbot** support for interactive learning

---

## 💼 Applications

- 🏢 **Enterprise Networks** – Detect early breaches
- 🎓 **Educational Institutes** – Teach cybersecurity hands-on
- 🏛 **Government Agencies** – Monitor secure digital environments

---

## 📁 Dataset

- Used **NSL-KDD** dataset: includes features like `duration`, `protocol_type`, `src_bytes`, `service`, etc.

---

## 🚀 Get Started

```bash
git clone https://github.com/Ejalandhar/major-project.git
cd nids-ml
pip install -r requirements.txt
streamlit run app.py

...................................................................................................................................................................
# 1. (Optional) Create virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# 2. Install dependencies
pip install -r requirements.txt

# 3. Convert raw data to CSV (if not already done)
python convert_to_csv.py

# 4. Train the ML model and save it
python train_model.py

# 5. Start the FastAPI backend server
uvicorn backend.app:app --reload

# 6. Open a new terminal for the frontend and run Streamlit
streamlit run frontend/dashboard.py
...........................................................................................................................................................................




