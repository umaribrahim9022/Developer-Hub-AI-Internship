# Task 4: General Health Support Chatbot (Prompt Engineering)

### 🎯 Objective
Built a medical assistant chatbot that provides empathetic and informational health advice while prioritizing user safety.

### 🤖 Model Used
- **Mistral-7B-Instruct-v0.2** (via Hugging Face Inference API).

### 💡 Key Features & Prompt Engineering
- **Safety Filters:** Redirects emergency queries (like "heart attack") to professional emergency services.
- **Non-Prescriptive:** Avoids giving specific dosages or prescriptions.
- **Medical Disclaimer:** Always advises consulting a human doctor.

### 📈 Key Insights
- Prompt engineering allowed a general LLM to act as a specialized assistant without the need for expensive training.