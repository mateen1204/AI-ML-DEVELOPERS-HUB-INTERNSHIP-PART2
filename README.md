# AI-ML-DEVELOPERS-HUB-INTERNSHIP-PART2
Machine Learning Project Portfolio: Deep Learning & Production Pipelines
Author: Mateen Asghar

Institution: COMSATS University Islamabad, Wah Campus

Focus: NLP, Computer Vision, and Automated ML Workflows

This repository features three specialized implementations designed to bridge the gap between academic theory and production-ready machine learning. All modules were developed using Python, PyTorch, and Scikit-learn.

📂 Project Modules
🔹 Module 1: News Topic Classification (NLP)
Architecture: Fine-tuned BERT (Bidirectional Encoder Representations from Transformers).

Objective: Categorization of news headlines into four major topics using the ag_news dataset.

Key Implementation Details: * Pre-training weight adaptation via bert-base-uncased.

Optimized tokenization strategy including attention masks and padding.

Deployment: A real-time web interface built with Gradio for instant model validation.

🔹 Module 2: Automated Customer Churn Pipeline
Methodology: End-to-End Scikit-learn Pipeline Construction.

Objective: Predicting customer attrition using a production-grade workflow.

Key Implementation Details: * Preprocessing: Automated ColumnTransformer for StandardScaler and OneHotEncoder.

Model: Random Forest Classifier optimized for high-dimensional tabular data.

Persistence: Serialized the final pipeline using Joblib for "One-Click" inference in live environments.

🔹 Module 3: Multimodal Housing Price Regression
Architecture: Dual-Branch Late Fusion Neural Network.

Objective: Fusing unstructured (Image) and structured (Tabular) data to predict real estate values.

Key Implementation Details: * CNN Branch: 3-layer Convolutional Neural Network for spatial feature extraction from property images.

MLP Branch: Dense layers for processing numerical metadata.

Evaluation: Performance benchmarks established using MAE and RMSE.

🖥️ Technical Note: Compute & Hardware Optimization
To ensure training stability for models exceeding 110M parameters (BERT), this project was migrated from a local environment to Google Colab.

GPU Acceleration: Utilized NVIDIA T4 Tensor Cores to handle heavy tensor computations and Mixed Precision (FP16) training.

Resource Management: Cloud migration prevented the kernel instability and VRAM overflows encountered on local consumer hardware during the fine-tuning process.

Efficiency: Reduced model convergence time from several hours (CPU-based) to under 15 minutes (GPU-based).

📥 Getting Started
Open in Colab: Upload the .ipynb files to Google Colab.

Enable GPU: Go to Runtime > Change runtime type > T4 GPU.

Install Requirements:

Bash
pip install torch torchvision transformers datasets scikit-learn gradio joblib
Execute: Run cells sequentially to view training logs and final metrics.

Submission Verification
Each notebook contains the finalized execution outputs, including training/validation loss curves and performance metrics as per the 6th-semester CS requirements.
