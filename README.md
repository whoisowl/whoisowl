```{=html}
<h1 align="center">
```
🖥️ Server Health CLI
```{=html}
</h1>
```
```{=html}
<p align="center">
```
A lightweight Python CLI for monitoring Linux & macOS system health.
```{=html}
</p>
```
```{=html}
<p align="center">
```
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

```{=html}
</p>
```
```{=html}
<p align="center">
```
🇺🇸 English • 🇮🇷 فارسی
```{=html}
</p>
```

------------------------------------------------------------------------

# 📸 Preview

> Add terminal screenshots in `assets/demo.png` and update this section:

``` markdown
<p align="center">
<img src="assets/demo.png" width="850">
</p>
```

------------------------------------------------------------------------

# ✨ Features

-   ⚡ Real-time CPU monitoring
-   🧠 Memory monitoring
-   💾 Disk monitoring
-   🔥 Top CPU & memory consuming processes
-   ⏱️ System uptime
-   👤 Hostname & current user
-   📄 JSON output
-   🔄 Watch mode
-   🚨 Configurable alert thresholds
-   🎨 Colored terminal output
-   ✅ Proper exit codes

------------------------------------------------------------------------

# 📚 Table of Contents

-   🇺🇸 English
-   🇮🇷 فارسی

------------------------------------------------------------------------

# 🇺🇸 English

## Overview

Server Health CLI is a lightweight Python-based command-line tool for
monitoring system health.

## Installation

``` bash
git clone https://github.com/whoisowl/server-health-cli.git
cd server-health-cli
pip install -r requirements.txt
```

## Usage

``` bash
python health_check.py
python health_check.py --json
python health_check.py --watch 5
python health_check.py --cpu-threshold 85 --memory-threshold 80 --disk-threshold 90
```

## Example Output

``` text
Hostname : MacBook-Pro
CPU      : 15%
Memory   : 42%
Disk     : 61%
Status   : Healthy
```

## Roadmap

-   [x] CPU Monitoring
-   [x] Memory Monitoring
-   [x] Disk Monitoring
-   [x] JSON Output
-   [x] Watch Mode
-   [ ] YAML Configuration
-   [ ] Docker Support
-   [ ] GitHub Actions Tests
-   [ ] Prometheus Exporter

------------------------------------------------------------------------

# 🇮🇷 فارسی

## معرفی

Server Health CLI یک ابزار خط فرمان سبک است که با Python توسعه داده شده
و برای بررسی وضعیت سیستم استفاده می‌شود.

## نصب

``` bash
git clone https://github.com/whoisowl/server-health-cli.git
cd server-health-cli
pip install -r requirements.txt
```

## اجرا

``` bash
python health_check.py
python health_check.py --json
python health_check.py --watch 5
python health_check.py --cpu-threshold 85 --memory-threshold 80 --disk-threshold 90
```

## برنامه‌های آینده

-   [x] مانیتورینگ CPU
-   [x] مانیتورینگ حافظه
-   [x] مانیتورینگ دیسک
-   [ ] پشتیبانی از Docker
-   [ ] تست خودکار
-   [ ] تنظیمات YAML

------------------------------------------------------------------------

# 🤝 Contributing

Pull Requests are welcome!

------------------------------------------------------------------------

# 📜 License

MIT License

------------------------------------------------------------------------

# 👨‍💻 Author

**Arian Salarian**

-   🎓 Software Engineering Student
-   ☁️ Aspiring DevOps Engineer
-   🌐 https://github.com/whoisowl

⭐ If you like this project, please give it a star!
