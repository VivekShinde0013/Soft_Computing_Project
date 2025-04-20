# 🚗 AI-Based Fuel Efficiency Optimizer using Genetic Algorithms

This project is a web application that simulates an AI-driven engine tuning system to optimize vehicle fuel efficiency using **Genetic Algorithms (GAs)** — a key technique in **soft computing**. It allows users to input real-time driving conditions (RPM, load, speed, temperature), then finds the most fuel-efficient engine settings dynamically.

---

## 🔍 Features

- 🧠 Soft computing approach with Genetic Algorithm
- ✅ Accepts live user inputs (RPM, load, temperature, speed)
- ⚙️ Optimizes key engine parameters:
  - Fuel Injection Timing
  - Air-Fuel Ratio (AFR)
  - Ignition Timing
  - Throttle Position
- 📊 Displays optimal configuration with an efficiency score
- 🌐 Simple and responsive frontend (HTML/CSS/JS)
- 🐍 Python (Flask) backend for computation

---

## 📁 Project Structure

fuel-efficiency-live-input/ ├── app.py # Flask server ├── ga_optimizer.py # Genetic Algorithm logic ├── templates/ │ └── index.html # Frontend HTML + JS ├── static/ │ └── style.css # Styling


---

## 🧪 How to Run

### 🛠 Requirements:
- Python 3.7+
- pip / pip3

### 🔧 Steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/fuel-efficiency-live-input.git
   cd fuel-efficiency-live-input

How to run in your PC--
1. intsall Flask-
   pip install flask
2.Run the app-
  python app.py
3.Open in browser-
  http://localhost:5000


How It Works--

User inputs real driving data

Backend runs a Genetic Algorithm:

Generates random engine settings

Evaluates them using a fitness function

Evolves the best ones over multiple generations

Displays the most fuel-efficient parameters

Example Output--
Input:
RPM = 3000, Load = 70%, Temp = 35°C, Speed = 100 km/h

Output:
Fuel Injection: 10.1
Air-Fuel Ratio: 14.68
Ignition Timing: 8.23
Throttle Position: 49.8
Efficiency Score: 77.85

/**This project is for educational and demonstration purposes. You are free to adapt or expand it.**/

/**Author**/
Vivek Madan Shinde,Kothapalem Satheesh
Lovely Professional University
Email: vivekshinde061@gmail.com/satheeshyadav85@gmail.com
Project Partner: Annamneedi Suresh Kumar, Raghav Kumar



