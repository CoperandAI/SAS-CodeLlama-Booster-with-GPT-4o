## SAS CodeLlama Booster with GPT-4o

### 📚 Overview
This project demonstrates an automated pipeline to enhance the SAS programming capabilities of the CodeLlama model using ChatGPT-4o as a teacher. The goal is to:

- Improve CodeLlama's SAS language understanding.
- Leverage ChatGPT-4o for code correction and optimization.
- Fine-tune CodeLlama with domain-specific SAS business logic.

### 🚀 Features
- **Automated Evaluation:** Identifies knowledge gaps in CodeLlama's SAS skills.
- **GPT-4o Knowledge Distillation:** Uses ChatGPT-4o for correcting and enhancing SAS code.
- **Fine-Tuning Workflow:** Incrementally improves CodeLlama's performance through selective retraining.
- **Business-Specific Customization:** Final model is infused with business-related SAS code.

### ⚙️ Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/CoperandAI/SAS-CodeLlama-Booster-with-GPT-4o.git
   cd sas-llm-enhancement
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure environment variables:
   ```bash
   cp .env.example .env
   # Add your OpenAI API key
   ```

### 🧠 Training Workflow

1. **Baseline Evaluation:** Evaluates CodeLlama's initial SAS performance.
2. **Gap Identification:** Flags weak SAS areas using BLEU scores.
3. **GPT-4o Correction Loop:** Automatically improves code quality with ChatGPT-4o.
4. **Knowledge Distillation:** Fine-tunes CodeLlama with corrected outputs.
5. **Domain Adaptation:** Infuses the model with business-specific SAS logic.

### 📊 Example Usage

To run the notebook:
```bash
jupyter notebook SAS-CodeLlama-Booster-with-GPT-4o.ipynb
```

### 📄 License
This project is licensed under the MIT License.

