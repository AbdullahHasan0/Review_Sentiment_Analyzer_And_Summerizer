# 📝 Review Insights NLP

A simple and effective NLP pipeline for extracting insights from product reviews.

## 🚀 Features

This project performs:

- ✅ Sentiment Classification — Determines if a review is Positive or Negative  
- 📚 Review Summarization — Generates concise summaries from long reviews

---

## 📂 Notebooks

- `training.ipynb` — Fine-tunes the DistilRoBERTa model on custom product review data for sentiment analysis
- `inference.ipynb` — Predicts sentiment and summarizes reviews using pre-trained models

---

## 🔧 Models Used

| Task | Model |
|------|-------|
| Sentiment Classification | DistilRoBERTa (fine-tuned) |
| Summarization | facebook/bart-large-cnn |

---

## 💾 Model Hosting

Due to issues with uploading large model files to GitHub, the fine-tuned sentiment model has been uploaded to the Hugging Face Hub.

Hugging Face Model: **Abdullah104/amazon_sentiment_analysis**

---

## 🛠️ How to Use

1. Clone this repository  
2. Install all dependencies using the command:
3. run the command `pip install -r requirements.txt` to download all the requirements
4. Run the `inference.ipynb` notebook to generate sentiment predictions and summaries for your input reviews.

---

## 📬 Contact

Created by **Syed Abdullah Hasan** — [Hugging Face Profile](https://huggingface.co/Abdullah104)

For questions or collaborations, feel free to reach out.

---

⭐ Star the repo if you find it helpful!
