This project introduces a deep learning model combined with Explainable AI (XAI) to classify skin burns into four categories: First-degree burns, Second-degree burns, Third-degree burns, and Healthy skin. The main goal is to ensure interpretability and transparency in predictions, which is critical for clinical decision-making.

Overview
Skin burn injuries require accurate and reliable classification for effective medical intervention. While deep learning models achieve high performance, their "black-box" nature limits adoption in healthcare. This project addresses this issue by integrating Grad-CAM (Gradient-weighted Class Activation Mapping), enabling users to visualize and understand the model's decision-making process.

Key Highlights:

Explainable AI (XAI): Grad-CAM heatmaps provide transparency in model predictions.
EfficientNetB0: A lightweight and powerful model for feature extraction.
Data Augmentation: Improves generalization using advanced techniques.
Performance: Achieved 94.4% accuracy on training data.
Explainable AI (XAI)
The project emphasizes transparency through Explainable AI techniques, ensuring that healthcare practitioners can validate and trust predictions. Grad-CAM visualizations highlight regions of interest in input images, allowing users to:

Identify the specific areas influencing predictions.
Verify that model focus aligns with clinical knowledge.
Improve decision-making confidence in critical medical applications.
Grad-CAM Features:
Heatmaps: Visualize areas influencing the model's predictions.
Overlay Visuals: Combine the original image with heatmaps for enhanced interpretability.
