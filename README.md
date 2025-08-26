🎥 YouTube Comment Sentiment Analyzer

A simple web app that fetches comments from any YouTube video and performs **real-time sentiment analysis** using a **RoBERTa transformer model** from Hugging Face.
The app is built with **Streamlit** for the frontend and `youtube-comment-downloader` for fetching comments — no dataset required!



 🚀 What This Project Does

* 🔗 Accepts a YouTube video link from the user
* 💬 Fetches comments (Top or Recent)
* 🤖 Classifies each comment into **Positive**, **Negative**, or **Neutral** sentiment
* 📊 Displays results in both **list format** and **visualizations (charts/percentages)**
* ⚡ Runs instantly with any YouTube video



🛠️ Tech Stack / Libraries Used

This project uses the following major libraries:

* **[Streamlit](https://streamlit.io/)** → For building the web app GUI
* **[Transformers (Hugging Face)](https://huggingface.co/transformers/)** → Pretrained `roberta-base-sentiment-latest` model
* **[Torch](https://pytorch.org/)** → Backend deep learning framework used by Transformers
* **[youtube-comment-downloader](https://pypi.org/project/youtube-comment-downloader/)** → To extract comments without API keys
* **scikit-learn** → For preprocessing & optional ML utilities
* **matplotlib / seaborn** → For plotting charts



 📦 Installation

1️⃣ Clone the repo


git clone https://github.com/your-username/youtube-sentiment-analyzer.git
cd youtube-sentiment-analyzer


### 2️⃣ Create a virtual environment


conda create -n yt-sentiment python=3.10
conda activate yt-sentiment



requirements.txt

pip install -r requirements.txt



## ▶️ Running the App

```bash
streamlit run app.py
```

Then open the **local URL** provided in the terminal (default: [http://localhost:8501](http://localhost:8501)).



## 📚 Example Workflow

1. Paste a YouTube video URL into the input box.
2. Choose the number of comments to fetch (e.g., 100).
3. Click "Analyze Sentiment".
4. View results:

   * Each comment labeled as **Positive/Negative/Neutral**
   * Overall distribution chart


## 🔮 Future Improvements

* 🌍 Multilingual sentiment support
* ☁️ Deploy on **Streamlit Cloud / Hugging Face Spaces**
* 🔎 Word cloud visualizations for top positive/negative words
* 📈 Export results to CSV


⚡ Built with ❤️ for learning NLP + Streamlit




