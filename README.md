# MarianMT-Hindi-English-NMT

🚧 **Research Project | Manuscript Under Preparation**

## Overview
## Framework Workflow


MarianMT-Hindi-English-NMT is a transformer-based Neural Machine Translation (NMT) framework for Hindi-to-English translation. The project leverages the MarianMT architecture and fine-tuning on the IIT Bombay Hindi-English Parallel Corpus to generate fluent, context-aware, and semantically accurate translations.

Unlike traditional Rule-Based Machine Translation (RBMT) and Statistical Machine Translation (SMT) systems, the framework utilizes self-attention and cross-attention mechanisms to capture contextual relationships and long-range dependencies during translation generation.

---

## Framework Components
## Experimental Pipeline

<p align="center">
  <img src="experimental pipeline.jpg" width="850">
</p>

- Data Collection & Preprocessing
- Tokenization using MarianTokenizer
- Transformer-Based Encoding
- Attention-Based Decoding
- MarianMT Fine-Tuning
- Translation Generation
- BLEU / TER / ChrF Evaluation

---

## Dataset

### IIT Bombay Hindi-English Parallel Corpus

- Public bilingual Hindi-English dataset
- Multiple domains including news, literature, and web text
- Train, validation, and test splits used for experimentation

---

## Experimental Configuration
## MarianMT Architecture

<p align="center">
  <img src="MarianMT Architecture.jpg" width="850">
</p>

## MarianMT Architecture

| Parameter | Value |
|------------|------------|
| Model | MarianMT (opus-mt-hi-en) |
| Architecture | Transformer Encoder-Decoder |
| Tokenizer | MarianTokenizer |
| Training Environment | Google Colab GPU |
| Evaluation Metrics | BLEU, TER, ChrF |

---

## Experimental Results

| Metric | Value |
|----------|----------|
| BLEU Score | 46.80 |
| Translation Direction | Hindi → English |
| Model | MarianMT |
| Dataset | IIT Bombay Parallel Corpus |

## BLEU Precision Analysis

<p align="center">
  <img src="BLEU PRECISION ANALYSIS .jpg" width="850">
</p>

## Qualitative Translation Performance


---

## Key Findings

- Achieved a BLEU score of 46.80 on Hindi-to-English translation tasks.
- Generated context-aware and semantically coherent English translations.
- Improved translation fluency compared to traditional translation approaches.
- Leveraged transfer learning through MarianMT fine-tuning.
- Demonstrated effective multilingual sequence learning using transformer architectures.

---

## Research Contributions

- Developed a transformer-based Hindi-to-English Neural Machine Translation framework.
- Fine-tuned MarianMT on the IIT Bombay Hindi-English Parallel Corpus.
- Integrated self-attention and cross-attention mechanisms for contextual translation.
- Evaluated performance using BLEU, TER, and ChrF metrics.

---

## Authors

- Rashi Bajpai
- Shubhranshu Shekhar Dash


---

## Status

📄 Research Manuscript Under Preparation
