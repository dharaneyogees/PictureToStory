# Picture to Story

Picture to Story is a simple pipeline that converts images into short stories using **Hugging Face transformers**.  
It first generates a caption from the photo and then uses that caption to produce a short story.

## 🛠 Tech Stack
- Python
- Hugging Face `transformers`
- PIL (Python Imaging Library)

## 🚀 How it works
1️⃣ It converts an **image** into a **caption**.  
2️⃣ It then uses this caption as a prompt to generate a **short story**.  
3️⃣ The photo and story are displayed side by side.

## Installation
```bash
pip install transformers Pillow
