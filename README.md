# 🌟 AI-Powered YouTube Content Moderation

## 🛠️ Project Overview
This project scrapes **YouTube video metadata and comments** to build a dataset for **AI-powered content moderation**. The scraped data is processed and analyzed using **NLP techniques, sentiment analysis, and data visualization** to detect spam, toxic comments, and categorize sentiments.

## 🚀 Features
- 🌐 **Web Scraping**: Extracts YouTube video titles, descriptions, comments, and metadata.
- 📝 **Data Cleaning**: Removes HTML tags, special characters, and stopwords.
- 👨‍💻 **Sentiment Analysis**: Classifies comments as Positive, Negative, or Neutral (VADER/BERT-based models).
- 🌀 **Spam & Toxic Comment Detection**: Uses keyword-based filtering.
- 📊 **Data Visualization**: Generates word clouds, bar charts, and sentiment distribution graphs.

## 📚 Project Structure
```
📂 youtube-content-moderation/
├── 📂 data/                 # Folder for datasets
│   ├── youtube_data.csv     # Cleaned dataset
│   ├── youtube_data.json    # JSON version of the dataset
│
├── 📂 scripts/              # Python scripts for different tasks
│   ├── scrape_youtube.py    # Web scraping script
│   ├── clean_data.py        # Data cleaning script
│   ├── sentiment_analysis.py # Sentiment classification script
│   ├── visualization.py     # Data visualization script
│
├── 📂 notebooks/            # Jupyter Notebooks for analysis
│   ├── data_analysis.ipynb  # Notebook for EDA & visualization
│
├── README.md                # Project documentation
├── requirements.txt         # Dependencies list
└── report.pdf / video.mp4   # (Optional) Short report/video explaining the approach
```

## 🌍 Installation & Setup
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/youtube-content-moderation.git
cd youtube-content-moderation
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Run the Web Scraper**
```bash
python scripts/scrape_youtube.py
```
### **4. Perform Sentiment Analysis**
```bash
python scripts/sentiment_analysis.py
```
### **5. Generate Visualizations**
```bash
python scripts/visualization.py
```

## 🌟 Sample Visualizations
- **Word Cloud**: Displays the most frequently used words in video comments.
- **Bar Chart**: Shows the distribution of video categories.
- **Sentiment Distribution**: Pie chart of positive, negative, and neutral comments.

## 🔮 Future Enhancements
- 🧠 **Improve sentiment analysis** using a BERT-based NLP model.
- 👁️ **Enhance spam detection** with machine learning.
- 🏢 **Deploy as a real-time AI-powered content moderation tool.**

## 💬 Contributing
Pull requests are welcome! Feel free to open an issue for discussions.

## ✨ Acknowledgments
Thanks to **OpenAI, YouTube API, and the AI community** for their valuable contributions.

---
📢 **Maintainer:** Minakshi Sharma | [Mins2203](https://github.com/Mins2203)

