
# 📱 Social Media Post & Caption Generator

✨ **Generate catchy captions, fun emojis, and trending hashtags for Instagram, LinkedIn, and Twitter using AI!**

## 🚀 Features
- AI-generated captions from a keyword or theme.
- Emojis chosen by analyzing the sentiment of the generated caption.
- Platform-specific hashtags mixed with prompt keywords.

## 📦 Installation

> Make sure you have Python 3.7+ installed.

```bash
# Clone this repository
git clone https://github.com/yourusername/social-caption-generator.git
cd social-caption-generator

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required libraries
pip install gradio transformers
```

## ▶️ Usage

Run the app:

```bash
python app.py
```

After running, Gradio will provide a local URL and a shareable public link.

## 🛠 How it works
- **Text Generation**: Uses GPT-2 to create captions.
- **Sentiment Analysis**: Determines the sentiment of the caption to choose suitable emojis.
- **Hashtags**: Extracts keywords and adds platform-specific trending tags.

## 📌 File Structure

```
.
├── app.py           # Main Python script
├── README.md        # Project README
└── requirements.txt # (Optional) dependencies list
```

> You can generate `requirements.txt` by running:
> ```bash
> pip freeze > requirements.txt
> ```

## ❤️ Credits

- [Gradio](https://gradio.app/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

## 📄 License

MIT License
