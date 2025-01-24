# Advanced Neural Network Architectures and Applications

This project explores advanced neural network techniques, addressing five key problems: generating optimal digit representations, detecting change points in time-series data, summarizing sequences, building deep CIFAR classifiers, and implementing contrastive learning. Each task demonstrates unique machine learning challenges and solutions, providing insights into different architectures like RNNs, CNNs, and embedding networks.


## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Requirements](#requirements)
- [File Output](#file-output)
- [License](#license)
- [Important Note](#important-note)


## Features

- **Most Likely Digits**:
  
  - Optimize and display digit images that maximize classification probabilities using different models
    
  - Compare features extracted by no-hidden-layer and deeper MNIST models
    
- **Change Point Detection**:
  
  - Train RNN and CNN models to identify change points in time-series data

  - Analyze model performance with visualizations of detection probability as a function of time from the change point
    
- **Sequence Summarization**:

  - Implement a non-neural algorithm for summarizing and querying sequences
    
  - Develop a neural network with embeddings and recurrent layers to learn summarization and query tasks
    
- **Delving Deeper**:

  - Construct and train a CIFAR-10 classifier with a focus on creating deep architectures (50–100 layers)
    
  - Use advanced techniques like normalization, dropout, and transfer learning to overcome training challenges

- **Contrastive Learning**: 

  - Implement contrastive loss for CIFAR-10, embedding similar classes closer and dissimilar classes farther

   - Visualize embeddings in 2D and analyze how the scatter plot evolves during training
  

## Usage


1. **Clone the repository**:

   ```bash
   git clone https://github.com/Kobe-Martinez/neural-network-experiments.git
   cd neural-network-experiments

2. **Run the notebook**:

  - Open the `.ipynb` file in Jupyter Notebook or JupyterLab

  - Execute cells sequentially to see the implementation and results

  - Modify hyperparameters or configurations as needed for further exploration
    

## Code Structure

- **Notebook**: 

  - `neural_network_analysis.ipynb`: Contains all data preprocessing, model definitions, training loops, and visualizations

- **Task Breakdown**:

  - Most Likely Digits: Optimize digit images for classification

  - Change Point Detection: Train and compare RNNs and CNNs for sequential anomaly detection

  - Sequence Summarization: Neural and non-neural approaches for sequence summarization

  - Deep CIFAR Classifier: Implementation of deep architectures for CIFAR-10

  - Contrastive Learning: Embedding CIFAR-10 classes with contrastive loss

## Requirements

- **Python**: 
  - 3.8 or later

- **Required libraries**:

  - `torch`

  - `torchvision`

  - `numpy`

  - `matplotlib`

  - `seaborn`

- **Install dependencies**:

  - `pip install torch torchvision numpy matplotlib seaborn`
 

## File Output

- **Visualizations**:
  
  - Optimized digit images for MNIST classification
    
  - Detection probability vs. time for change point detection
    
  - CIFAR embeddings plotted over time
    
  - Training and testing losses for various models
    
- **Metrics and Logs**:
  
  - Saved results for analyzing model performance
 

## License

This project is licensed under the MIT License. See the LICENSE file for details.


## Important Note

This code is intended for educational purposes only; Use this repository responsibly.
