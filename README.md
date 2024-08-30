# Social Media Engagement Classifier

This project is a machine learning-based tool designed to classify social media posts like photos, links, statuses, and videos based on engagement metrics such as likes, shares, comments, and reactions.

## Project Overview

Social media platforms have become essential for content engagement and communication. This project leverages machine learning techniques to classify posts into different content types, providing insights into which types of content generate the most engagement.

### Key Features

- **Data Collection:** Utilizes the "Exploring Social Media Reactions: A Deep Dive into Engagement Metrics Across Different Post Types" dataset from Kaggle.
- **Machine Learning Models:** Implements K-Nearest Neighbors (KNN), Logistic Regression, and Multi-Layer Perceptron (MLP) models for classification.
- **Model Evaluation:** Models are evaluated based on accuracy, F1-score, and other relevant metrics, with MLP showing the highest performance.
- **User Interface:** Allows users to classify posts using trained models and view model performance metrics.

### Results

- **MLP Model:** Achieved the highest accuracy, outperforming KNN and Logistic Regression.
- **Engagement Insights:** Photos tend to generate more likes and positive reactions, while videos receive more shares and comments.

### Practical Implications

This project provides valuable insights for businesses and content creators to optimize their social media strategies, enhancing user engagement and improving marketing campaigns.

## Future Work

- **Feature Expansion:** Incorporating features like post timing and hashtags.
- **User Feedback:** Integrating user feedback to refine the classifier over time.

## Getting Started

To set up the project locally:

1. Install Python 3.x.
2. Clone the repository and navigate to the project directory.
3. Install the required libraries: `pip install -r requirements.txt`.
4. Load the dataset and run the models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
