# 🛡️ Jailbreak Prompt Detection using BERT-based Models

Этот проект направлен на исследование и построение моделей машинного обучения для **автоматической детекции jailbreak-промптов** — то есть вредоносных, обходных или манипулятивных пользовательских запросов к большим языковым моделям (LLMs), с целью заставить их нарушить правила безопасности.

Модели обучены классифицировать промпты как:
- ✅ **Безопасные**
- 🚫 **Jailbreak / вредоносные**

---

## 📂 Структура репозитория

```plaintext
LLMs/
│
├── EuroBert/
│   └── EuroBERT_for_jailbreak_prompts.ipynb
│
├── Bert/
│   ├── BERT_for_jailbreak_prompts_for_Llama_CHUNKS.ipynb
│   └── Model_Evaluation_Report_(1)_(2).ipynb
