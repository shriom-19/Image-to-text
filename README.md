
# 🖼️ Image Describer with Hugging Face BLIP

A simple Gradio-based app that generates **human-like image captions** using the [BLIP](https://huggingface.co/Salesforce/blip-image-captioning-base) model from Hugging Face Transformers.

---

## 🚀 Demo

Upload an image and get a caption!

🔗 **Run in Colab**: [Open Notebook](https://colab.research.google.com/drive/1kUn3CDXLp5uISGNrD9PYNx_61R7L8NNm)

---

## 💻 Features

- Upload any image to get a **caption**.
- Powered by **BLIP (Salesforce)** via Hugging Face.
- Fast, easy-to-use **Gradio UI**.
- **GPU** support (CUDA) for fast generation.

---

## 🧠 Model Used

- **BLIP (Bootstrapped Language Image Pretraining)**  
  Hugging Face Model: [`Salesforce/blip-image-captioning-base`](https://huggingface.co/Salesforce/blip-image-captioning-base)

---

## 🛠️ Installation

### 📌 Option 1: Run in Colab
No setup needed! Just open this notebook:  
[🔗 View Notebook](https://colab.research.google.com/drive/1kUn3CDXLp5uISGNrD9PYNx_61R7L8NNm)

### 📌 Option 2: Run Locally
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

# Install required packages
pip install -r requirements.txt

# Run the Gradio app
python app.py

---

### 📥 Save README in Colab (if needed):

```python
readme_text = '''<PASTE ENTIRE TEXT ABOVE HERE>'''

with open("README.md", "w") as f:
    f.write(readme_text)

print("✅ README.md saved.")
