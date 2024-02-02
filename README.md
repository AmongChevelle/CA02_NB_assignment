# CA02_NB_assignment
Introduction

This email Spam Classifier is a machine learning project that employs the Naive Bayes algorithm to distinguish between spam and non-spam emails. The objective of this project is to accurately classify emails, helping users filter out unwanted or harmful content. This README outlines how to set up and use the classifier, including installing necessary dependencies, running the classifier, and understanding its structure and components.

Usage

To use the email Spam Classifier, ensure you have your dataset of emails organized into 'train-mails' and 'test-mails' directories. These directories should be in the same folder as your .ipynb notebook file for the relative paths to work correctly. Run the Jupyter notebook to train the model and classify the emails.

Features

Utilizes the Naive Bayes algorithm for email classification.
Includes detailed code comments and explanations to understand the machine learning process.
Configurable dictionary size for feature extraction.

Dependencies

NumPy
scikit-learn

Configuration

Ensure your data folders (train-mails and test-mails) are located in the same directory as the Jupyter notebook. This setup is crucial for the relative paths used in the code to function correctly across different environments.

Examples

The notebook demonstrates the classifier's performance with varying dictionary sizes, showing how the accuracy changes with different feature set sizes. This exploration provides insights into the trade-offs between model complexity and performance.

Troubleshooting

If you encounter issues with relative paths, verify that your .ipynb file is in the same directory as the train-mails and test-mails folders. Additionally, ensure all dependencies are installed correctly.

Contributors

Mason Dosher
Aaron Sornborger
Kevin Tu
