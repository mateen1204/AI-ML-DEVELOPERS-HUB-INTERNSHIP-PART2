🚀 Machine Learning & Data Engineering Portfolio

Author: Mateen Asghar
Institution: Developer Hub & Co. | COMSATS University
Position: ML Research Intern | March 2026
This repository showcases a series of advanced Machine Learning implementations ranging from Computer Vision and Multimodal Architectures to LLM-driven Automation.

📂 Project Portfolio

Task 1: News Classification via BERT Transformers
Model: bert-base-uncased
Focus: High-accuracy text classification using multi-head attention mechanisms.
Implementation: Developed a fine-tuning pipeline for the AG News dataset, achieving state-of-the-art convergence using GPU-accelerated training.

Task 2: Robust Production Pipelines (Churn Analysis)
Framework: Scikit-learn & Joblib
Focus: Feature engineering and model persistence.
Implementation: Built a modular pipeline using ColumnTransformer to handle categorical encoding and numerical scaling simultaneously, ensuring zero data leakage between training and validation sets.


Task 3: Deep Feature Extraction (Convolutional Neural Networks)
Architecture: Custom 3-Layer CNN
Focus: Spatial feature mapping and image preprocessing.
Implementation: Developed a vision-based model optimized for high-dimensional image data, utilizing ReLU activation and Dropout layers to mitigate overfitting.


Task 4: Multimodal Housing Analytics (Late Fusion)
Architecture: Dual-Stream MLP + CNN
Focus: Hybrid Data Fusion for Predictive Modeling.
Implementation: A sophisticated regression model that concatenates visual property features with tabular metadata (sqft, bedrooms, etc.) to estimate market value.
Evaluation: Optimized using RMSE and MAE to ensure high pricing precision.


Task 5: Automated Ticket Tagging (LLM Zero-Shot vs. Fine-Tuning)
Model: Llama-3.2-3B & DistilBERT
Focus: Scalable NLP Automation.
Implementation: A comparative analysis of Zero-Shot/Few-Shot prompting via the 2026 Hugging Face Router API against a specialized fine-tuned classifier.
Result: Demonstrated how LLMs can drastically reduce cold-start problems in ticket categorization.



🖥️ Computing & Optimization
To handle the memory-intensive nature of the BERT and Multimodal tasks, the entire suite was deployed on Google Colab Cloud Infrastructure:
GPU Computing: Utilized NVIDIA T4 hardware to manage large batch sizes.
Efficiency: Implemented FP16 Mixed Precision to optimize VRAM usage and speed up training cycles.


🛠️ Installation & Execution
Bash
pip install torch transformers tensorflow scikit-learn pandas matplotlib
Open the .ipynb files in Google Colab.


Enable GPU Acceleration in the runtime settings.
Ensure your Hugging Face API Token is active for Task 5's LLM inference.
