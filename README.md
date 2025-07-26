# 📊 YouTube Channel Data Extractor & SQL Analysis

This project extracts metadata from a YouTube channel using the YouTube Data API v3 and saves it in CSV format. The extracted data includes channel metadata, list of all uploaded videos, and individual video statistics. The goal is to analyze YouTube channel performance using SQL in the next phase.

---

## ✅ Features

- Extracts **channel-level metadata** (title, description, subscribers, etc.)
- Gets **video-level metadata** (title, publish date, description)
- Fetches **video stats** (views, likes, comments)
- Saves all data to **CSV files** for further SQL-based analysis

---

## 🛠 Tech Stack

- Python 3
- YouTube Data API v3
- Pandas
- Google API Client
- SQL (for analysis in Phase 2)

---

## 📁 Output Files

| File Name                  | Description                             |
|---------------------------|-----------------------------------------|
| `channel_list.csv`        | List of tracked channels                |
| `channel_meta_data.csv`   | Metadata about the channel              |
| `all_video_list.csv`      | All uploaded videos with basic info     |
| `youtube_video_stats.csv` | Video stats like views, likes, comments |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

