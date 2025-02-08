# NEUROVERSE - AI Counselor

NEUROVERSE is an AI-powered chatbot designed to provide empathetic and supportive responses based on user input and emotional analysis. Built with **LLaMA 3.2-3B-Instruct** and an emotion classification model, NEUROVERSE acts as a friendly counselor, helping users navigate their feelings in a non-therapeutic, conversational manner.

---

## Features
- **Emotion Detection**: Uses a BERT-based model to analyze user sentiment.
- **Conversational AI**: Provides supportive and concise responses tailored to the user's emotions.
- **GPU Acceleration**: Supports CUDA for efficient processing.
- **Personalized Experience**: Asks for the user's name and brief description to customize responses.
- **LLaMA 3.2-3B-Instruct Integration**: Generates natural and human-like responses.
- **Optimized Sampling**: Uses `temperature`, `top-k`, and `top-p` strategies for diverse and meaningful replies.

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/RK-NerdyBirdy/Neuroverse
cd Neuroverse
```

### 2. Install Dependencies
Ensure you have Python 3.8+ installed, then run:
```bash
pip install torch transformers huggingface_hub
```

### 3. Login to Hugging Face Hub
To access the LLaMA model, authenticate with your Hugging Face account:
```python
from huggingface_hub import login
login(token="YOUR_HF_TOKEN")
```

---

## Model Details
- **LLaMA 3.2-3B-Instruct**: Used for generating natural language responses.
- **BERT-Based Emotion Model**: Analyzes text and classifies emotions.
- **CUDA Support**: Optimized for GPUs.
- **Hyperparameter Tuning**: Uses `top-k`, `top-p`, and `temperature` for creativity and coherence.

---

## Future Enhancements
- **Multimodal Input Support** (Text + Voice Recognition)
- **Fine-tuned Emotion Model** for PTSD & Mental Health Counseling
- **Web & Mobile App Integration**

---

## License
This project is open-source under the MIT License.

---

## Contributors
- Maneet Gupta ([GitHub Profile](https://github.com/RK-NerdyBirdy))

