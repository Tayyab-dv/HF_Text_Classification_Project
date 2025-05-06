# HF_Text_Classification_Project

# 🍔 Food vs Not Food - Text Classification with Hugging Face Transformers

This project implements a **binary text classification model** using Hugging Face Transformers to categorize text as either food-related or not food-related. The model is trained on a labeled dataset of image captions and deployed using Gradio for real-time inference.

---

## 🚀 Features

- 🤗 Built with `Transformers`, `datasets`, and `evaluate` from Hugging Face
- 📊 Efficient preprocessing, label encoding, and train/test splitting
- 🧠 Fine-tuned `distilbert-base-uncased` for high performance on binary classification
- 🌐 Deployed with an interactive Gradio UI for demo and testing
- 📈 Real-time prediction with input texts like: `"I love sushi!"` ➝ `food`

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Hugging Face Transformers & Datasets
- PyTorch
- Gradio (for deployment)
- Google Colab / Jupyter Notebook

---

## 🧪 Training & Evaluation

- Model: `distilbert-base-uncased` fine-tuned for text classification
- Metrics: Accuracy, Loss
- Train/Test Split: 80/20 with random seed for reproducibility

---

## 📊 Example Predictions

| Text                                           | Predicted Label |
|------------------------------------------------|------------------|
| "This sandwich tastes amazing!"               | food             |
| "The sunset was beautiful over the hills."    | not_food         |

---

## 🌐 Live Demo

> 👉 Try it out here: [Gradio Demo](https://huggingface.co/spaces/itayyab/food_not_food_text_classifier_demo)

---



