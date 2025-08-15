# Implementing-a-Simple-Neural-Network-for-Handwritten-Digit-Recognition-Utilizing-Softmax-Activation

<span style="font-size: 18px; color: #000000; font-weight: bold;">Context</span>
<p style="font-size: 15px; color: #333333;"> This repository illustrates a simple neural network built using tensorflow for handwritten digit recognition. The objective of this project was to gain a deeper understanding of neural networks and to familiarise myself wit the tensorflow library. </p>

<span style="font-size: 18px; color: #000000; font-weight: bold;">Dataset</span>
<p style="font-size: 15px; color: #333333;"> This dataset was extracted from an exercise available in Andrew Ng's Machine Learning Specialization. The specialization is offered by Stanford Online and DeepLearning.AI through Coursera. </p>

<span style="font-size: 18px; color: #000000; font-weight: bold;">Process</span>
<p style="font-size: 15px; color: #333333;"> A neural network with three dense layers was designed for this task. The input layer contained 25 units with ReLU activation, followed by one hidden layer with 15 units, also using ReLU activation. The output layer had 10 units with a linear activation, with the softmax operation integrated into the loss function during training for improved numerical stability. The model was trained using the Sparse Categorical Crossentropy loss function and optimized with the Adam (Adaptive Moment) optimizer. After 60 epochs of training, the model achieved over 95% accuracy. </p>

<span style="font-size: 18px; color: #000000; font-weight: bold;">Acknowledgements</span>
<p style="font-size: 16px; color: #333333;"> The dataset and much of the inspiration for the implementation of the neural network comes from the <a href="https://www.coursera.org/specializations/machine-learning-introduction" target="_blank" style="color: #0066cc; text-decoration: none;">Machine Learning Specialization</a>. This project is based on the teachings and exercises from the specialization’s second course, <a href="https://www.coursera.org/learn/advanced-learning-algorithms" target="_blank" style="color: #0066cc; text-decoration: none;"> Advanced Learning Algorithms </a>.
  
Special thanks to Andrew Ng for providing a clear and accessible introduction to core machine learning concepts.
</p>
