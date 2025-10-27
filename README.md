# 🔍 SIEM Log Analyzer & Threat Detection

A Python-based Security Information and Event Management (SIEM) simulator for real-time log analysis and threat detection.

## 🚀 Features
- **Real-time Log Processing** - Parse system, firewall, and application logs
- **Threat Detection** - Identify brute force attacks, port scanning, suspicious activity
- **Security Dashboard** - Interactive visualization with attack metrics
- **Alert System** - Configurable rules for security incidents

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Matplotlib/Plotly for visualization
- Regex for log parsing
- SQLite for data storage

## 📦 Installation
```bash
git clone https://github.com/your-username/siem-log-analyzer.git
cd siem-log-analyzer
pip install -r requirements.txt
🎯 Usage
python
python src/log_parser.py --file access.log
python src/threat_detection.py --real-time
📊 Sample Detection Rules
Failed login attempts (>5/minute from single IP)

Port scanning activity

Geographic anomalies

Unusual working hours access

📄 License
MIT License - see LICENSE file for details.

⚠️ Disclaimer
For educational and authorized testing purposes only.
