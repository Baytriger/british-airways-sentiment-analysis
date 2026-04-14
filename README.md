
# British Airways Sentiment Analysis

NLP-based sentiment analysis of British Airways customer reviews, including polarity scoring, automated responses, and structured output generation for insight extraction.

---

##  Overview

Customer reviews contain valuable insights into airline service quality. This project analyzes British Airways customer feedback to classify sentiment and uncover patterns in customer satisfaction and dissatisfaction.

---

##  Objectives

* Classify reviews into **Positive, Negative, and Neutral**
* Measure sentiment polarity (-1 to +1)
* Generate automated response suggestions
* Export structured outputs for further analysis

---

##  Methodology

* Text preprocessing using Python
* Sentiment analysis using TextBlob
* Rule-based classification using polarity thresholds
* Automated response generation based on sentiment

---

##  Sentiment Categories

* **Positive** → favorable experiences and satisfaction
* **Negative** → complaints and dissatisfaction
* **Neutral** → mixed or unclear feedback

---

##  Outputs

This project generates:

* `analyzed_reviews.csv` → full dataset with sentiment & polarity
* `positive_reviews.csv` → filtered positive reviews
* `negative_reviews.csv` → filtered negative reviews
* `neutral_reviews.csv` → filtered neutral reviews
* `report.html` → visual sentiment analysis report

---

##  How to Run

```bash
pip install -r requirements.txt
python app.py
```

---

##  Project Structure

* `src/` → sentiment logic
* `outputs/` → generated results and reports
* `app.py` → main execution script
* - data/ → dataset (not included or sample only)

---

##  Tech Stack

* Python
* Pandas
* TextBlob (NLP)

---

##  Key Insight

This project demonstrates how unstructured customer feedback can be transformed into structured insights to support service improvement and decision-making.

---

