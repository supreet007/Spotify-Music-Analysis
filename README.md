# Spotify Music Analysis

## 📌 Introduction
This repository contains a Power BI dashboard designed to analyze **Spotify's most streamed songs** dataset until the year **2023**. The dashboard provides insights into total streams, individual track analysis, and trends across different months and artists.

![alexander-shatov-JlO3-oY5ZlQ-unsplash](https://github.com/user-attachments/assets/15e06b9b-ed26-465c-817b-510762e21c95)



## 📊 Features
- **Total Streams Analysis**: View overall streaming counts.
- **Track-Specific Insights**: Analyze energy, speechiness, liveness, danceability, and key metrics of a song.
- **Monthly Breakdown**: Check the total number of tracks and their average streams for each month.
- **Top 5 Most Streamed Songs**: Displays the most streamed tracks dynamically based on the selected time range and artist.
- **Interactive Filtering**: Select a **date range** and **artist** to focus on specific insights.
- **Graphical Trends**: Visualize streaming activity over time.

## 📂 Project Structure
```
Spotify_Dashboard/
│-- dataset/              # Contains raw data files (CSV, Excel, etc.)
|    │-- "Spotify Most Streamed Songs 2023 Dataset.xlsx"  # Streamed data in Excel format
│-- screenshots/          # Images of the dashboard preview
│   │-- spotify_dashboard.png  # Dashboard screenshot
|    │-- spotify_dashboard2.png  # Dashboard screenshot
│-- Spotify_Dashboard.pbix  # Power BI report file
│-- README.md             # Project documentation
```

## 📥 Dataset Information
The dataset includes:
- **Most Streamed Songs** till 2023.
- Track attributes such as **energy, speechiness, liveness, danceability, mode, and key**.
- Streaming counts by **month and artist**.

## 🚀 How to Use
### **1. Installation**
- Download and install **Power BI Desktop** from [Microsoft's official site](https://powerbi.microsoft.com/desktop/).

### **2. Clone the Repository**
```bash
git clone https://github.com/supreet007/Spotify-Music-Analysis.git
```

### **3. Open the Dashboard**
- Navigate to the project folder and open `Spotify_Dashboard.pbix` in Power BI Desktop.
- Load the dataset files from the `dataset/` folder.
- Refresh the dataset if required and explore the dashboard.

## 📷 Dashboard Preview
![Spotify dashboard](https://github.com/user-attachments/assets/30af828f-ce38-4b3b-ae41-7ca2ecbd4c4e)

![Spotify dashboard 2](https://github.com/user-attachments/assets/864a0bf1-4e78-47f8-b9cc-e4bb7fad607d)



## 🔄 Updating the Dashboard
1. Modify the dataset or Power BI report as needed.
2. Save the changes in `Spotify_Dashboard.pbix`.
3. Commit and push the updated files to GitHub:
```bash
git add .
git commit -m "Updated Spotify dashboard"
git push origin main
```

## 📬 Contact
For any queries or support, reach out via GitHub Issues or email: `supreet2804@gmail.com`.

---
**Enjoy Analyzing! 🎶📊**
