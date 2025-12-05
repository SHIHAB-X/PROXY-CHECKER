🚀 PROXY-CHECKER

A Powerful Proxy Validation Tool
By Abdur Rahim | GitHub: SHIHAB-X

---

📌 Overview

PROXY-CHECKER is a comprehensive Python-based tool for validating and analyzing proxies. It supports multiple protocols, checks anonymity levels, geolocation, and exports results in user-friendly formats.

---

✨ Features

✅ Single Proxy Check – Validate any proxy instantly
✅ Multi-Protocol Support – HTTP, HTTPS, SOCKS4, SOCKS5
✅ Geolocation Lookup – Country, City, ISP details
✅ Anonymity Testing – Transparent/Anonymous/Elite
✅ Batch Processing – Check multiple proxies at once
✅ Export Results – Save as JSON or CSV
✅ IP Information – Get your current public IP

---

🛠 Installation & Usage

1. Clone Repository

```bash
git clone https://github.com/SHIHAB-X/PROXY-CHECKER.git
cd PROXY-CHECKER
```

2. Install Dependencies

```bash
pip install requests
```

3. Run the Tool

```bash
python3 Checker.py
```

---

📊 Main Menu Options

```
1. CHECK PROXY (Single Type)
2. CHECK ALL PROXY TYPES
3. CHECK PROXY WITH GEOLOCATION
4. CHECK ANONYMITY LEVEL
5. BATCH CHECK & EXPORT
6. CHECK IP
7. Exit
```

---

📝 Usage Examples

Single Proxy Check

```bash
Enter proxy (format: ip:port): 123.45.67.89:8080
Select type (HTTP/HTTPS/SOCKS4/SOCKS5): HTTP
```

Batch Check

```bash
Enter filename (proxies.txt): proxies.txt
Select export format (JSON/CSV): JSON
```

---

📤 Export Formats

JSON Output Example

```json
{
  "proxy": "123.45.67.89:8080",
  "type": "HTTP",
  "status": "Alive",
  "response_time": "1.23s",
  "country": "United States",
  "city": "New York",
  "anonymity": "Elite"
}
```

CSV Output Example

```
proxy,type,status,response_time,country,city
123.45.67.89:8080,HTTP,Alive,1.23s,United States,New York
```

---

🤝 Support & Contact

📧 GitHub: SHIHAB-X
📱 Telegram: FLASH CYBER HUB

---

⚠️ Disclaimer

This tool is for educational and legitimate testing purposes only. Always use proxies responsibly and respect website terms of service.

---

📄 License

This project is for educational purposes.

---

⭐ Star the repo if you find it useful!
