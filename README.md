# 🔎 recon-toolkit

> *“Know your target before your target knows you.”*
> — codex-regex

![Status](https://img.shields.io/badge/status-in%20development-00ff88?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Ethics](https://img.shields.io/badge/use-ethical%20only-red?style=flat-square)

-----

## 📌 What Is This?

A beginner-friendly collection of Python scripts for **passive reconnaissance** — gathering information about a target without directly interacting with it.

Built by a cybersecurity analyst learning Python in public. Every script is documented, explained, and written to be understood — not just run.

> ⚠️ **Ethical Use Only.** These tools are for learning, CTFs, and authorized testing only. Never use on systems you don’t own or have permission to test.

-----

## 🛠️ Tools Included

|Script             |What It Does                     |Status       |
|-------------------|---------------------------------|-------------|
|`whois_lookup.py`  |Looks up domain registration info|✅ Ready      |
|`dns_recon.py`     |Finds DNS records for a domain   |✅ Ready      |
|`port_scanner.py`  |Basic TCP port scanner           |✅ Ready      |
|`header_grabber.py`|Grabs HTTP headers from a URL    |✅ Ready      |
|`subdomain_enum.py`|Enumerates subdomains            |🚧 Coming Soon|

-----

## 🚀 Getting Started

### Requirements

```bash
pip install requests dnspython python-whois
```

### Run a script

```bash
# WHOIS lookup
python whois_lookup.py example.com

# DNS recon
python dns_recon.py example.com

# Port scanner
python port_scanner.py example.com

# Header grabber
python header_grabber.py https://example.com
```

-----

## 📁 Folder Structure

```
recon-toolkit/
│
├── whois_lookup.py       # WHOIS domain lookup
├── dns_recon.py          # DNS record enumeration
├── port_scanner.py       # TCP port scanner
├── header_grabber.py     # HTTP header grabber
├── requirements.txt      # Dependencies
└── README.md             # You are here
```

-----

## 👩‍💻 About This Project

This is my first Python project. I built it while learning both Python and cybersecurity at the same time — so if you’re a beginner too, this repo is for you.

Every script is heavily commented so you can read it like a tutorial, not just a tool.

-----

## 📬 Find Me

[![GitHub](https://img.shields.io/badge/GitHub-codex--regex-181717?style=flat-square&logo=github)](https://github.com/codex-regex)

-----

*Learning in public. Breaking things ethically. One script at a time.* 🔐
