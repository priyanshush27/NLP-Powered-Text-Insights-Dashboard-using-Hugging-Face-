# NLP-Powered-Text-Insights-Dashboard-using-Hugging-Face-
NLP‑Powered Text Insights Dashboard using Hugging Face models. Analyzes 1,000+ text inputs to extract sentiment, emotions, and key phrases with advanced preprocessing. Interactive dashboards deliver actionable insights in seconds through word clouds, emotion charts, and sentiment bars.
# NLP-Powered Text Insights Dashboard

An interactive platform built with **Streamlit** and **Hugging Face transformer models** to analyze text data.  
The dashboard supports both **manual text input** and **CSV file uploads**, delivering insights such as **word clouds, n-gram analysis, emotion detection, sentiment analysis, tone classification, and text summarization**.

---

## 📌 Project Overview
This project demonstrates how **Natural Language Processing (NLP)** can transform raw text into actionable insights.  
Users can input text or upload CSV files, and the system applies preprocessing, NLP models, and visualization techniques to generate clear, interactive results.

---

## 🛠️ Code Structure
The repository is organized into three main Python files:

- **`app.py`** → Streamlit interface  
  - Provides the user-facing dashboard  
  - Handles text input or CSV upload  
  - Calls preprocessing and NLP functions to display results interactively  

- **`text_cleaner.py`** → Text preprocessing  
  - Cleans raw text using **spaCy**  
  - Performs lemmatization, stop word removal, and n-gram extraction  
  - Ensures higher data quality for analysis  

- **`nlp_functions.py`** → NLP model functions  
  - Executes Hugging Face transformer models  
  - Functions include:  
    - `show_wordcloud()` → Generate word clouds  
    - `plot_top_ngrams_bar_chart()` → Visualize n-grams  
    - `detect_emotions()` → Emotion detection  
    - `detect_overall_sentiment_avg()` → Sentiment analysis  
    - `classify_custom()` → Tone of speech classification  
    - `summarize_large_text()` → Text summarization  

---

## 🚀 Features
- **Text Input Mode:** Enter text manually and analyze instantly  
- **CSV Upload Mode:** Upload datasets and filter columns for text analysis  
- **Preprocessing:** Lemmatization, stop word removal, n-gram extraction  
- **Visualizations:** Word clouds, bar charts, emotion tables, sentiment scores  
- **NLP Insights:** Emotion detection, sentiment analysis, tone classification, text summarization  
- **Interactive UI:** Built with Streamlit for real-time results  

---

## 📂 Project Structure
├── app.py             # Streamlit interface ├── text_cleaner.py    # Text preprocessing with spaCy ├── nlp_functions.py   # NLP functions using Hugging Face ├── requirements.txt   # Dependencies └── README.md          # Project documentation


---

## ⚡ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://https://github.com/priyanshush27/NLP-Powered-Text-Insights-Dashboard-using-Hugging-Face-
   
2. - Install dependencies:
   - pip install -r requirements.txt

3. Download spaCy model (for lemmatization): 
    python -m spacy download en_core_web_sm

4. Run the Streamlit app:
   streamlit run app.py

5. - Open the local URL (usually http://localhost:8501) in your browser and start analyzing text.

📊 Results
- Successfully cleaned and lemmatized raw text using spaCy, ensuring consistent tokens for analysis
- Generated word clouds and n‑gram charts that highlight frequent terms and contextual patterns
- Delivered real‑time emotion and sentiment detection using Hugging Face models
- Enabled tone of speech classification and text summarization directly within the Streamlit interface
- Provided an interactive dashboard where insights are available in seconds for both text input and CSV uploads

##📫 Contact

Created by Priyanshu
- LinkedIn(https://www.linkedin.com/in/priyanshu-s-9b030a366/?trk=opento_sprofile_topcard)
- GitHub(https://github.com/priyanshush27)

