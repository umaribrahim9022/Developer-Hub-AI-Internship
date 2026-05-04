# Task 5: Mental Health Support Chatbot (Fine-Tuning)

### 🎯 Objective
To create a specialized chatbot that responds with high empathy to users experiencing stress, anxiety, or emotional distress.

### 📚 Dataset for Fine-Tuning
- **EmpatheticDialogues (Facebook AI):** A dataset of 25k human conversations grounded in specific emotional contexts.

### 🛠 Technical Implementation
- **Base Model:** `DistilGPT2` (Lightweight version of GPT-2).
- **Fine-Tuning:** Used Hugging Face **Trainer API** to update model weights on empathetic conversation pairs.
- **Preprocessing:** Tokenization and padding handled via Transformers library.

### 📈 Key Results
- The model transitioned from generic responses to supportive, emotionally aware dialogues.
- Fine-tuning proved effective for personality and tone adjustment in LLMs.