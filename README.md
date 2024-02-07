# Intention Call Classifier for Call Center using Generative AI

## Overview
This project aims to develop a sophisticated Intention Call Classifier tailored for Call Centers, leveraging the power of Generative AI. Utilizing advanced machine learning and natural language processing (NLP) techniques, this system is designed to accurately classify and understand the intentions behind customer calls, thereby enhancing customer service efficiency and effectiveness.

## Project Structure
The project is organized into several key directories, each serving a specific purpose in the development and deployment of the classifier:

- `data`: Contains all the datasets used for training, testing, and validation. This includes raw call data, interim processed files, and archived datasets.
- `docs`: Documentation-related materials, including quality assurance documents, accuracy metrics, and confusion matrices for model evaluations.
- `model`: Directory reserved for storing trained model files and related metadata.
- `notebooks`: Jupyter notebooks for exploratory data analysis (EDA), model training, evaluation, and other research and development activities.
- `reports`: Contains generated reports, diagrams (e.g., solution architecture), and images used for documentation and presentation purposes.
- `src`: Source code for the project, including scripts for data preprocessing, model training, inference, and utility functions.

## Data
The data directory is categorized into several subfolders:

- `archive`: Historical datasets used for model training and backtesting.
- `interim`: Intermediate data files generated during preprocessing or model inference.
- `raw1`, `raw2`, `raw3_health`: Raw call data files representing different batches or segments of the data collection process.
- Specific datasets for different intentions (e.g., health-related calls, emergency-related calls) and different versions of transcript data.

## Documentation
Quality-related documents are stored in the `docs` directory. These documents include performance metrics, confusion matrices, and accuracy tables that provide insights into the model's classification capabilities.

## Models
The `model` directory is intended to store the trained models and is crucial for versioning and maintaining different iterations of the AI models.

## Notebooks
This section includes Jupyter notebooks categorized into subdirectories based on their purpose:

- `colab`: Notebooks intended to be run in Google Colab, primarily for tasks like model fine-tuning.
- `eda`: Notebooks for exploratory data analysis on different datasets.
- `eval`: Evaluation notebooks to assess the performance of various models like GPT-3.5, LLama 2, and their fine-tuned versions.
- `genData`: Notebooks used for data generation and preprocessing tasks.
- `intention`: Notebooks focused on intention classification tasks using different models and approaches.
- `quality`: Notebooks used for quality assessment and script generation for call data.

## Reports
The `reports` directory contains architectural diagrams and other imagery that support the documentation and presentation of the project's structure and results.

## Source Code
The `src` directory contains the source code necessary for executing the project's data processing, model training, and inference operations.

## Getting Started
To get started with this project:

1. Clone the repository to your local machine.
2. Ensure you have the necessary libraries and dependencies installed by referring to the `requirements.txt` file.
3. Explore the `notebooks` directory to understand the data analysis, model training, and evaluation processes.
4. Train your model using the data provided in the `data` directory.
5. Test the model performance using the scripts in the `src` directory.

## Contribution
Contributions are welcome. If you wish to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Feel free to adjust or add sections as per the specific needs of your project!
