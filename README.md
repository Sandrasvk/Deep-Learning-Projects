# Advanced Deep Learning Series: Spatial & Sequential Modeling

​This repository serves as a technical portfolio featuring five distinct Deep Learning projects. The series documents a transition from foundational neural networks to high-complexity architectures, specifically focusing on Convolutional Neural Networks (CNN) for spatial feature extraction and Long Short-Term Memory (LSTM) networks for sequential data analysis.

​🚀 Technical Highlights
​Architectural Diversity: Implementation of both Recurrent (LSTM) and Convolutional (CNN) layers.
​Deep Stacking: Design of multi-layered networks with optimized filter depths (32-128 filters).
​Production Pipeline: Full end-to-end workflow from raw image preprocessing with OpenCV/PIL
​Optimization: Advanced use of Dropout, Batch Normalization, and Adam optimizers to manage gradient flow and prevent overfitting.

​📂 The 5-Project Series

​1. Sequential Analysis with LSTMs

​Focuses on temporal dependencies. By utilizing LSTM layers, this project addresses the vanishing gradient problem inherent in standard RNNs, allowing the model to "remember" long-term patterns in sequential data.

​2. Foundational CNN Baseline

​The entry-point into Computer Vision. Implemented a Sequential pipeline to transform raw pixel data into spatial feature maps using Conv2D and MaxPooling layers.
​3. Stabilized Deep Architectures

​Introduced Regularization techniques. This project focuses on model generalization by integrating Dropout and Batch Normalization to bridge the gap between training and validation accuracy.

​4. High-Capacity Feature Extraction

​A scaled-up architecture designed for high-diversity datasets. Increased filter density across multiple convolutional blocks to capture intricate pathological textures and patterns.
​
​🛠️ Tooling & Stack
​Core Frameworks: TensorFlow, Keras

​Preprocessing: OpenCV, PIL (Pillow)

​Data Analysis: NumPy, Pandas, Scikit-Learn

​Visualization: Matplotlib, Seaborn
