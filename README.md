# Sarcasm Detection: A Comparative Study of BiLSTM, BERT, and DistilBERT

A course case study comparing the performance of classical and transformer-based models for sarcasm detection using the [News Headlines Dataset for Sarcasm Detection](https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection).

## 🧩 Project Overview
This work explores multiple NLP architectures:
- **BiLSTM** with GloVe embeddings
- **BERT (bert-base-uncased)**
- **DistilBERT (distilbert-base-uncased)**
- **Helinivan/english-sarcasm-detector** (pre-trained)

## 🧠 Objectives
- Develop a sentiment analysis system that handles sarcastic expressions.
- Compare model performance on structured datasets.
- Explore GPT-based sarcasm detection and potential in Indic languages.

## 📊 Results Summary
| Model | Accuracy | Parameters |
|--------|-----------|-------------|
| BiLSTM (GloVe 100d) | 85–87% | ~3–12M |
| BERT (base-uncased) | 92.5% | 110M |
| DistilBERT | 91.8% | 66M |
| Pre-trained (Helinivan) | 94% | 110M |

DistilBERT achieved near-BERT accuracy with almost half the parameters, validating its efficiency for real-world NLP tasks.

## 💡 Key Insights
- Transformer-based models generalize far better than LSTM on sarcasm-rich data.
- Models trained on structured datasets still struggle with “simple” sarcasm requiring broader contextual cues.
- GPT-based models (e.g., CustomGPT “Oh Great, Another Monday”) show potential for proactive sarcasm detection in real-world use.

## 🧭 Future Scope
- Sarcasm detection in Indic languages such as Tamil and Hindi.
- Fine-tuning multilingual transformers (Tamil LLaMA, IndicBERT).
- Building multimodal sarcasm detection systems integrating tone and text.

## 📚 References
[See presentation PDF](docs/PA2212044010023_07_54.pdf)

## 🔗 Links
- Dataset: [News Headlines for Sarcasm Detection](https://github.com/rishabhmisra/News-Headlines-Dataset-For-Sarcasm-Detection)
- Pretrained Model: [helinivan/english-sarcasm-detector](https://huggingface.co/helinivan/english-sarcasm-detector)
- GPT: [Oh Great, Another Monday](https://chat.openai.com/g/g-85C0MB3G8-oh-great-another-monday)
