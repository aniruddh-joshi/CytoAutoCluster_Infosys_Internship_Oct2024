#SEMI-SUPERVISED DEEP CLUSTERING ON CYTOMETRY DATA

Project Overview
Cytometry data is widely used in biological and medical research to identify and characterize cell populations. However, its high-dimensional complexity often hinders traditional analysis methods. This project introduces a semi-supervised machine learning model for deep clustering, leveraging both labeled and unlabeled data to enhance accuracy and interpretability. Advanced techniques like correlation analysis and t-SNE further support the model’s ability to uncover meaningful patterns in complex biological datasets.

Introduction
Cytometry data plays a vital role in understanding cell populations, but its analysis is challenging due to the intricate relationships within the data. By combining semi-supervised learning with deep clustering, this project addresses these challenges, enabling more accurate cell population identification. The model integrates labeled and unlabeled data to capture nuanced patterns and improve performance. Visualization tools like t-SNE provide insights, making the results both interpretable and actionable for research applications.
Methodology
•	Preprocessing: Standardizing cytometry data and splitting it into labeled and unlabeled subsets.
•	Model Design: Using semi-supervised deep clustering algorithms to leverage both data types.
•	Dimensionality Reduction: Applying t-SNE and correlation analysis for better visualization.
•	Evaluation: Assessing clustering performance using metrics like silhouette score and accuracy against labeled data.

 Dataset Details
•	Source: Levine 32-dimensional cytometry dataset.
•	Features: Includes markers like CD45, CD3, and CD19, with both labeled and unlabeled subsets.
•	Size: High-dimensional dataset with over 100,000 events.

 Results
•	Enhanced clustering performance compared to traditional methods.
•	Meaningful visualizations showing distinct cell populations.
•	Improved interpretability using t-SNE and feature correlation.

 Future Work
•	Extending the model to support additional cytometry datasets.
•	Exploring other semi-supervised learning algorithms for further improvements.
•	Developing a user-friendly interface for biologists to analyze their own data.
Getting Started
1. Clone the repository:
   ```bash
   git clone< https://github.com/rustiiiiiii/CytoAutoCluster_Infosys_Internship_Oct2024.git>
   cd < https://github.com/rustiiiiiii/CytoAutoCluster_Infosys_Internship_Oct2024.git>

License
This project is licensed under the MIT License.
Acknowledgments
•	Data Source:  Levine 32-dimensional dataset.
•	Inspiration from recent advancements in semi-supervised and deep learning techniques.


