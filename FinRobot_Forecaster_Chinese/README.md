# FinRobot_Forecaster_Chinese

A lightweight, organized project for Chinese financial time series forecasting and inference.

## Features
- Data processing and download: `Ashare_data.py`
- Training scripts (e.g., LoRA): `train_lora.py`
- Inference data pipeline: `Inference_datapipe.py`
- Common utilities: `utils.py`
- Training config: `configs/ds_config_zero2.json`
- Data formulation notebook: `notebooks/Formulate_training_data.ipynb`

## Installation
```bash
pip install -r requirements.txt
```

## Quick Start
- Training:
```bash
python train_lora.py
```
- Inference:
```bash
python Inference_datapipe.py
```

## Project Structure
```
FinRobot_Forecaster_Chinese/
├── Ashare_data.py
├── Inference_datapipe.py
├── train_lora.py
├── utils.py
├── requirements.txt
├── configs/
│   └── ds_config_zero2.json
└── notebooks/
    └── Formulate_training_data.ipynb
```

## License
This project is reorganized from the original directory for better structure and naming consistency.
