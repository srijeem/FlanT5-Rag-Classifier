**Overview**

Classify BBC news articles into complexity levels (`easy`, `medium`, `hard`)
- **Model**: `google/flan-t5-base`
- **Fine-tuning**: LoRA (Low-Rank Adaptation) for parameter-efficient training
- **Retrieval**: FAISS + Sentence Transformers (RAG)
- **Deployment**: Streamlit web app exposed via ngrok (Google Colab compatible)


**Tech**

Python, PyTorch, HuggingFace Transformers, LoRA / PEFT, Retrieval-Augmented Generation (RAG), FAISS, Sentence Transformers, scikit-learn, Streamlit,


**Outcome**


Achieved 86.8% accuracy and 0.74 macro-F1 on held-out test data. Retrieval-augmented prompting improved model reasoning and consistency over zero-shot baselines.The final solution was deployed as an interactive Streamlit web application for real-time, context-aware text classification.




 
