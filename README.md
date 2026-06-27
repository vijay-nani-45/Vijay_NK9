readme_text = r"""# English → Hindi Translation with LLM

## Overview
This project translates 100 English sentences into Hindi using Facebook's NLLB‑200‑distilled‑600M model (an open‑source LLM) and evaluates the translations with BLEU, chrF, and TER scores.

## Workflow
1. **Dataset** – Parallel English‑Hindi sentences from `eng.txt` and `hin.txt` are cleaned (Assignment 1) and stored in `cleaned_dataset.xlsx`.
2. **Translation** – The first 100 rows of `cleaned_dataset.xlsx` are fed into the NLLB model to produce Hindi translations.
3. **Evaluation** – The generated translations are compared against the reference Hindi sentences using:
   - BLEU (n‑gram precision)
   - chrF (character n‑gram F‑score)
   - TER (Translation Edit Rate)

## Files in this Project
- `cleaned_dataset.xlsx` – Cleaned parallel data (output of Assignment 1)
- `translations.xlsx` – Original English + Model‑generated Hindi translations
- `scores.txt` – Evaluation metric scores
- `Assignment2_translation.py` / Colab notebook – Translation & scoring script

## Requirements
Install dependencies (if running locally):
```bash
pip install pandas openpyxl transformers torch sacrebleu



readme_text = r"""# English → Hindi Translation with LLM

## Overview
This project translates 100 English sentences into Hindi using Facebook's NLLB‑200‑distilled‑600M model (an open‑source LLM) and evaluates the translations with BLEU, chrF, and TER scores.

## Workflow
1. **Dataset** – Parallel English‑Hindi sentences from `eng.txt` and `hin.txt` are cleaned (Assignment 1) and stored in `cleaned_dataset.xlsx`.
2. **Translation** – The first 100 rows of `cleaned_dataset.xlsx` are fed into the NLLB model to produce Hindi translations.
3. **Evaluation** – The generated translations are compared against the reference Hindi sentences using:
   - BLEU (n‑gram precision)
   - chrF (character n‑gram F‑score)
   - TER (Translation Edit Rate)

## Files in this Project
- `cleaned_dataset.xlsx` – Cleaned parallel data (output of Assignment 1)
- `translations.xlsx` – Original English + Model‑generated Hindi translations
- `scores.txt` – Evaluation metric scores
- `Assignment2_translation.py` / Colab notebook – Translation & scoring script

## Requirements
Install dependencies (if running locally):
```bash
pip install pandas openpyxl transformers torch sacrebleu



