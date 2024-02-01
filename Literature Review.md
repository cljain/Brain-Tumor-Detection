Chapter 2: Literature Review

2.1 Neural network.
A neural network, inspired by the functioning of biological neural networks in the human brain, is a computational model comprising interconnected nodes known as neurons or artificial neurons. These nodes are arranged in layers, consisting of an input layer, one or more hidden layers, and an output layer.

The fundamental unit of a neural network is the artificial neuron. Every neuron accepts input signals, processes them by applying weights that are modified during training, and generates an output signal. The connection strengths (weights) among neurons dictate the influence of one neuron's output on another. The learning process in a neural network includes refining these weights in response to the disparity between the network's predictions and the desired output.

Fig. 1.Neural network




2.2 Convolutional neural networks

Neural networks, a subset of machine learning crucial to deep learning algorithms, are structured with layers of nodes, comprising an input layer, hidden layers, and an output layer. Nodes are interconnected, possessing assigned weights and thresholds. Activation takes place when a node's output exceeds a designated threshold, facilitating the transmission of data to the next layer; otherwise, data is not forwarded.
While the main focus of this discussion has been on feedforward networks, various types of neural networks are tailored to diverse data and use cases. For example, recurrent neural networks excel in tasks like natural language processing and speech recognition, whereas convolutional neural networks (CNNs) are widely used in classification and computer vision applications. Before the advent of CNNs, labor-intensive manual methods were employed for extracting features in image object identification. However, convolutional neural networks transformed image classification by leveraging linear algebra, especially matrix multiplication, to identify patterns within images. Despite their computational intensity, which requires the use of graphics processing units (GPUs) for training, CNNs provide a scalable and efficient approach to image recognition and object classification.
2.2.1 How do convolutional neural networks work?
Convolutional neural networks (CNNs) stand out for their exceptional performance in handling inputs like images, speech, or audio signals. Structurally, CNNs consist of three primary types of layers:
1. Convolutional Layer:
   The initial layer in a convolutional network, convolutional layers may be succeeded by additional convolutional or pooling layers. These layers play a crucial role in enhancing the network's ability to discern intricate details within the input data. In the early stages, convolutional layers focus on identifying basic features like colors and edges.
2. Pooling Layer:
   Following the convolutional layers, pooling layers are instrumental in down-sampling or reducing the spatial dimensions of the data. This step helps in retaining essential information while decreasing computational load. Pooling layers contribute to the network's overall efficiency in recognizing patterns.
3. Fully-Connected (FC) Layer:
   The fully-connected layer serves as the concluding segment of the CNN. As the data progresses through the network, layers become progressively complex, enabling the identification of larger portions of the input, such as distinct shapes or features. Ultimately, the final layer of the fully-connected layer is pivotal in making high-level predictions or classifications.







Fig. 2.CNN Architecture
