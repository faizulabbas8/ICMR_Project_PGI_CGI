# README.md
# ICMR LLM Prescription Parser

## Objective
Extract structured data (Doctor, Patient, Medicines, Dosage, Instructions) from handwritten prescriptions using BLIP-2 multimodal LLM.

## Method
- Preprocessing: thresholding + resizing
- LLM used: BLIP-2 FLAN T5
- Output: Structured JSON using prompt engineering

## Run Pipeline
```bash
python run_pipeline.py
```

## Evaluate
```bash
python eval_pipeline.py
```

## Dependencies
```bash
pip install -r requirements.txt
