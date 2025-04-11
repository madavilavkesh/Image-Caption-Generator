# Image Caption Generator

This web app generates human-like captions for images using the **BLIP** model by Salesforce. Upload an image and get an AI-generated caption instantly.

---

## 🚀 Live Demo

👉 [Try it on Hugging Face Spaces](https://huggingface.co/spaces/madavilavkesh/Image_Caption_Generator)

---

## 🧠 About the Model

We use [Salesforce's BLIP image captioning model](https://huggingface.co/Salesforce/blip-image-captioning-large), which leverages a **vision-language pretraining approach**. BLIP combines a vision encoder (ViT) and a language decoder (GPT-like) to understand image content and generate natural language descriptions. It's trained on large-scale image-text pairs and is among the best performing models for image captioning tasks.

---

## 🖼️ Screenshots

### 🧑‍💻 Interface Preview

![Interface Screenshot](Screenshot_Interface.png)

---

### 🖼️ Test Image 1

**Input:**
![IMG_1](IMG_1.jpg)

**Caption Output:**
![Screenshot IMG 1](Screenshot_IMG_1.png)

---

### 🖼️ Test Image 2

**Input:**
![IMG_2](IMG_2.jpg)

**Caption Output:**
![Screenshot IMG 2](Screenshot_IMG_2.png)

---

## 📋 Features

- Generates natural image captions using `Salesforce/blip-image-captioning-large`
- Easy-to-use Gradio interface
- Runs on Hugging Face Spaces

---

## 🧑‍💻 Run Locally or on Colab

### 📥 Option 1: Download `.ipynb` and Run on Colab


### 🖥️ Option 2: Clone and Run Locally

```bash
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator
pip install -r requirements.txt
python app.py
