## Log Anomaly Detector

A Python-based toolkit that parses Apache/Nginx logs, applies anomaly detection rules, and flags suspicious activity such as request floods, suspicious IPs, or SQLi attempts.

## Features

- Apache/Nginx/custom log parser
- Pattern matching (regex-based rules)
- Frequency and spike scoring
- IP categorization and whitelist support
- Modular rule system

## To-Do
- Docker support
- Web UI for reviewing flagged logs
- YAML rule engine
- Integrate fail2ban-style IP blacklisting

 ## Getting Started

```bash
git clone https://github.com/youruser/log-anomaly-detector.git
cd log-anomaly-detector
pip install -r requirements.txt
python scripts/run_detector.py --log examples/sample_logs/nginx.log
