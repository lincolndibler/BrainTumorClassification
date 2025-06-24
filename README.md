# BrainTumorClassification

BrainTumorProject/
│
├── run.ipynb                  # Master dashboard for loading/summarizing all models
├── models/
│   ├── mobilenet_model.ipynb  # Train & evaluate MobileNetV2
│   ├── resnet_model.ipynb     # Train & evaluate ResNet50
│   ├── effnet_model.ipynb     # Train & evaluate EfficientNetB0
│
├── utils.py                   # Data loading and visualization utilities
├── evaluation.py              # ModelEvaluator class + Grad-CAM visual tools
├── models.py                  # Functions to build and train each architecture
│
├── saved_models/              # Trained `.keras` or `.h5` model files
│   ├── mobilenet_model.keras
│   ├── resnet_model.keras
│   ├── effnet_model.keras
│
├── data/
│   ├── Training/
│   └── Testing/

