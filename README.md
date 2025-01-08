# Harnessing Effectiveness of ResNet-50 and EfficientNet for Few-Shot Learning

## Abstract
Inspired by the concept of human intelligencelearning and expanded upon with several examples – severalstep learning focused on computers that can classify images in
a similar way. This article covers the interesting field of sparse
learning, focusing on comparing its implementation using two
popular deep learning networks: ResNet and EfficientNet. Little
learning has the potential to be effective on tasks where obtaining
large data sets is expensive or impossible; This allows machines to
mimic humans’ ability to learn and expand from small samples,
thus opening up possibilities in the field of various types of
diagnostics, personalized recommendations, systems and robotics.
Our main goal is to measure and compare the accuracy achieved
by these models when learning on limited datasets and to show
that EfficientNet achieves better accuracy when it requires fewer
parameters and computational resources compared to ResNet50. We considered VGG-flowers dataset for comparison. Our
results show that Narrow EfficientNet outperforms ResNet-50 in
terms of overall accuracy (85.20% vs. 84.30%), precision (85.60%
vs. 85.40%), recall (85.30% vs. 84.50%) and F1 acquisition
(85.45% vs. 84.95%). This suggests that EfficientNet’s emphasis
on computational efficiency and parallelism may provide a slight
advantage on limited data.

## Overview

Few-shot learning aims to enable machine learning models to generalize effectively with minimal data, mimicking human-like learning capabilities. This study benchmarks ResNet-50 and EfficientNet in terms of:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### Key Findings

- **EfficientNet** outperformed ResNet-50 across all metrics with slightly better accuracy (85.20% vs. 84.30%) and computational efficiency.
- ResNet-50, while slightly less accurate, remains a strong candidate due to its robustness and scalability.

## Methodology

1. **Dataset:**  
   - **VGG-Flowers Dataset**: Contains 4242 images categorized into five classes: Chamomile, Tulip, Rose, Sunflower, and Dandelion.
   - Features include diverse resolutions and proportions, suitable for real-world classification tasks.

2. **Architectures:**
   - **ResNet-50:** A 50-layer residual network optimized for deep learning tasks with strong gradient flow.
   - **EfficientNet:** A compact, scalable model emphasizing efficiency by balancing depth, width, and resolution.

3. **Evaluation Metrics:**
   - Accuracy, Precision, Recall, and F1-Score.

## Performance Comparison

| Model       | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| ResNet-50   | 84.30%   | 85.40%    | 84.50% | 84.95%   |
| EfficientNet| 85.20%   | 85.60%    | 85.30% | 85.45%   |

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/vivekyeli7/Harnessing-Effectiveness-of-ResNet-50-and-EfficientNet-for-Few-Shot-Learning.git
   cd project-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the experiment:
   ```bash
   python main.py
   ```

## Results 
EfficientNet demonstrates superior performance on limited datasets, emphasizing its suitability for low-resource environments. However, ResNet-50 remains a viable alternative in scenarios requiring extensive model depth.

## References
This project builds upon the methodologies and findings outlined in:

Tan, M., & Le, Q. V. (2019). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.
He, K., Zhang, X., Ren, S., Sun, J. (2016). Deep residual learning for image recognition.

