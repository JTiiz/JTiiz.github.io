# Portfolio · Jesús Ramírez Durán


**Website:** https://jtiiz.github.io

## Projects
- [YouTube QA Chatbot (RAG)](https://github.com/JTiiz/yt_chatbot_final): ask any YouTube video a question and get the answer with a link to the exact minute; captions or Whisper ingestion, RAGAS-evaluated retrieval (LangChain, ChromaDB, Gradio, Docker)
- [Review Intelligence Dashboard](https://github.com/JTiiz/project-amazon-review-classifier-nlp-ai): sentiment and product-category classification of Amazon reviews with fine-tuned RoBERTa models, plus AI market reports ([models on Hugging Face](https://huggingface.co/jramduran); Transformers, LoRA, Streamlit, Docker)
- [Image recognition with CNN and transfer learning](https://github.com/JTiiz/CNN-project): recognises 10 animals in a photo and compares a CNN built from scratch with EfficientNetV2-S, ConvNeXt-Tiny and a Vision Transformer on the same test set, up to 99.2% accuracy ([models on Hugging Face](https://huggingface.co/models?search=jramduran/animals10); Keras 3 on PyTorch, Transformers, Flask, Docker)
- [Fake news classifier](https://github.com/JTiiz/natural-processing-models): comparison of three NLP pipelines (scikit-learn)
- [Iron Kaggle](https://github.com/JTiiz/iron-kaggle): forecasts the daily sales of 1,115 Rossmann stores and compares linear regression, a decision tree, random forest and gradient boosting on the last 6 weeks of data, up to R² 0.921 ([models on Hugging Face](https://huggingface.co/models?search=jramduran/rossmann-sales); scikit-learn, pandas, Streamlit, Plotly, Docker)

## Structure
- `index.html`: main page with the projects, the way of working and the stack
- `career.html`: experience, education and awards (`trayectoria.html` redirects here)
- `style.css`: styles shared by both pages
- `i18n.js`: translations and language selector
- `videos/`: demo videos in MP4 (see `videos/LEEME.txt`)

## Languages
The site is written in English. `i18n.js` switches it to Spanish, French, German, Italian or Portuguese according to the visitor's browser language, and the selector in the menu lets them change it. To edit a text, change the English in the HTML and the same key in `i18n.js`.
