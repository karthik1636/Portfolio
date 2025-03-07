# Project Overview

## Title
Comparative Analysis of LSTM and Transformer Models for Emotion Detection in Text

## Objective
To evaluate the effectiveness of LSTM and Transformer models in detecting a range of emotions from textual data to enhance applications in fields like customer feedback analysis, mental health assessments, and market research.

## Data Description
- **Size:** Over 839,000 annotated text entries.
- **Sources:** The dataset comprises various text entries annotated with emotional labels, sourced from publicly available NLP datasets and supplemented by manually annotated entries to ensure diversity and comprehensiveness.

## Methodology

### 1. Data Preprocessing:
- **Tokenization:** Text data was converted into tokens where each unique word was mapped to an integer, creating a structured form that the models could process.
- **Padding:** To handle inputs of varying lengths, sequences were padded to a uniform length, ensuring consistent input size for the neural networks.

### 2. Model Architecture:
- **LSTM (Long Short-Term Memory):** Utilizes a series of gates to control the flow of information, addressing the vanishing gradient problem common in traditional RNNs.
- **Transformer:** Employs an encoder-decoder structure with multi-headed self-attention, facilitating parallel processing and a better understanding of context in sequences.

### 3. Training:
- **GPU:** Conducted on an RTX 4060 GPU.
- **LSTM:** Models trained over 5 epochs, each lasting approximately 12 minutes.
- **Transformer:** Models trained more efficiently, with total training time of 14 minutes.

## Performance Metrics
- **Accuracy:**
  - **LSTM:** Achieved a peak validation accuracy of 99.2%.
  - **Transformer:** Achieved a peak validation accuracy of 99.8%.
- **Precision, Recall, and F1-Score:**
  - **LSTM:** Precision: 99.2%, Recall: 99.1%, F1-Score: 99.15%
  - **Transformer:** Precision: 99.8%, Recall: 99.75%, F1-Score: 99.775%

## Quantifiable Results
- **Error Rates:** Both models demonstrated low error rates with significant improvements in recognizing overlapping emotions and reducing context-dependent misclassifications.
- **Data Efficiency:** Transformer models proved to be more data-efficient, achieving higher accuracies with shorter training times compared to LSTM models.

## Project Impact
- **Academic Contribution:** The project adds substantial value to the academic community by providing insights into the capabilities and limitations of LSTM and Transformer models in emotion detection, a critical area of NLP.
- **Commercial Application:** In commercial settings, the improved accuracy and efficiency of these models can be directly applied to enhance customer interaction platforms, sentiment analysis tools, and mental health monitoring applications.
- **Technical Advancement:** Demonstrates the practical application of advanced neural network architectures in handling large datasets and complex NLP tasks, setting a benchmark for future research and development in the field.

## Tools and Technologies Used
- **Programming Languages:** Python.
- **Libraries and Frameworks:** TensorFlow for LSTM, PyTorch for Transformer models.
- **Hardware:** Utilized high-performance computing with NVIDIA RTX 4060 GPU.
