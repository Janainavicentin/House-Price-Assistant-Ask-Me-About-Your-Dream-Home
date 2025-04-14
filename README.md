# 🏡 House Price Assistant – Ask Me About Your Dream Home

Welcome to my AI-powered assistant that helps users ask natural questions about historical house prices in London boroughs — just like you would ask a real estate agent or AI avatar!

This project simulates the kind of interaction a user might have with a virtual property assistant, similar to those being developed in PropTech companies like **ModelProp**.

---

## ✨ Features

- 💬 **Natural Language Understanding**  
  Ask questions like:
  - “What was the house price in Hackney in 2015?”
  - “Was Barking and Dagenham expensive in 2016?”
  - “How much was a flat in Camden in 2012?”

- 📊 **Real Housing Data**  
  Data comes from the [London Datastore](https://data.london.gov.uk/dataset/land-registry-house-prices-borough), covering over 20 years of house prices across all London boroughs.

- 🎛️ **Interactive Chat Interface**  
  Built using [Gradio](https://www.gradio.app/), the assistant is clean, simple, and ready for demo.

- 🔊 **Voice-Ready (Optional)**  
  The assistant can convert responses into spoken audio using [gTTS](https://pypi.org/project/gTTS/) – ideal for future integration with AI avatars.

---

## 🧰 Tech Stack

| Tool        | Purpose                         |
|-------------|----------------------------------|
| `pandas`    | Data loading and filtering       |
| `gTTS`      | Text-to-speech generation (optional) |
| `gradio`    | Web interface for interaction    |
| `Jupyter`   | Notebook development             |

---

## 🧠 What I Learned

- How to extract **intent (year + location)** from messy human language
- How to connect real-world data to an **AI assistant interface**
- How to make AI feel more **natural, friendly, and helpful**
- How to simulate **conversation testing (Stage 6)** and **integration (Stage 7)** in an AI pipeline

---

## 📁 Files Included

- `house_price_assistant.ipynb` – main notebook
- `land-registry-house-prices-borough.csv` – sample dataset from London Datastore
- Optional: `output.mp3` (generated audio file if you use the voice feature)

---

## 🚀 How to Run It Locally

1. Clone this repo  
2. Open the notebook in Jupyter  
3. Install dependencies:
   ```bash
   pip install pandas gradio gTTS
