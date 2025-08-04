# RSNA-Intracranial-Aneurysm-Detection
Brain aneurysm detection using machine learning on CTA, MRA, and MRI images. Entry for the RSNA-ASNR-SNIS-ESNR challenge on automated aneurysm diagnosis.

🧠 RSNA Intracranial Aneurysm Detection
This project implements a full DICOM processing and deep learning inference pipeline for the RSNA 2024 Intracranial Aneurysm Detection Challenge.

Using pretrained CNN and Transformer backbones (e.g. EfficientNetV2, ConvNeXt, Swin Transformer), the system detects and localizes aneurysms across multiple brain arteries from CTA, MRA, and MRI studies.

Key Features:

🏥 End-to-end DICOM series processing with modality-specific windowing

🔎 Multi-channel input creation (MIP, std projection, center slice)

🧠 Metadata fusion (age, sex) for enhanced classification

⚙️ Model ensemble with optional Test-Time Augmentation (TTA)

📦 Compatible with Kaggle's competition inference API

