## 🩺 Xray-Vision: Multimodal Interpretation of Chest X-Rays
Xray-Vision is a multimodal machine learning pipeline designed to assist in the interpretation of chest X-rays by combining unsupervised image clustering with natural language processing (NLP) techniques. This approach aims to make radiological insights more accessible, especially in settings with limited medical expertise.

# 🔍 Project Overview
Image Clustering: Utilizes a pre-trained VGG16 model to extract features from chest X-ray images, followed by KMeans clustering to group similar images based on visual patterns.

Report Summarization: Applies transformer-based models (e.g., BART) to summarize associated radiology reports, providing concise descriptions of common findings within each image cluster.

Clinical Term Analysis: Implements co-occurrence analysis and similarity assessments of clinical terms in reports to understand language patterns and their diagnostic relevance.

# 💡 Key Features
Unsupervised Learning: Enables pattern discovery without the need for labeled data, facilitating scalable analysis of large datasets.

Multimodal Integration: Combines visual and textual data to provide a comprehensive understanding of chest X-rays.

Accessibility: Aims to support healthcare professionals by offering preliminary insights, potentially reducing diagnostic workload.

# 📁 Repository Contents
Capstone_Final_Project.ipynb: Main Jupyter notebook containing the implementation of the pipeline.

USML_Project_Report.pdf: Detailed report outlining the project's methodology and findings.

X-ray vision.pptx: Presentation summarizing the project's objectives and results.
