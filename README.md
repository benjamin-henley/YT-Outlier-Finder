# YouTube Small Channel Outlier Finder

A Python machine learning tool that identifies statistical outliers in YouTube niches, specifically targeting small channels with viral potential.

## Features
- **YouTube API Integration**: Fetches real-time video metrics
- **Shorts Filtering**: Automatically excludes YouTube Shorts (<60s)
- **ML Outlier Detection**: Uses Isolation Forest algorithm from scikit-learn
- **Viral Coefficient Analysis**: Calculates views/subscribers ratio
- **Small Channel Focus**: Highlights channels under 100k subscribers
- **CSV Export**: Generates detailed analytics reports
- **Customizable Search**: Analyze any YouTube niche

## How It Works
1. **Data Collection**: Uses YouTube Data API v3 to fetch videos
2. **Preprocessing**: Filters Shorts, calculates engagement metrics
3. **Machine Learning**: Applies Isolation Forest for anomaly detection
4. **Analysis**: Identifies outliers based on viral coefficient and engagement
5. **Reporting**: Outputs ranked results and CSV files

## Installation

### Prerequisites
- Python 3.11+
- YouTube Data API v3 Key

### 1. Clone Repository
```bash
git clone https://github.com/YOURUSERNAME/YT-Outlier-Finder.git
cd YT-Outlier-Finder
