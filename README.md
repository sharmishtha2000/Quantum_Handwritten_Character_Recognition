# Handwritten Character Recognition Using Quanvolutional Neural Networks

This project is an implementation of English handwritten character recognition using Quanvolutional Neural Networks, and is based on "Quanvolutional Neural Networks: Powering Image Recognition with Quantum Circuits" (https://arxiv.org/pdf/1904.04767.pdf).

<img width="816" alt="Model Architecture" src="https://user-images.githubusercontent.com/55295304/184307082-2a76d3f5-2cb0-4f00-9654-a126d18ee5e3.png">

The model was tested with different sizes of training dataset and was compared with the same CNN model without Quantum layer. The results are shown below:

<img width="400" alt="Graph" src="https://user-images.githubusercontent.com/55295304/184307503-6f4fdbcd-1d6b-4ba0-99a2-155df0790dd6.png">

Apart from the size of the training dataset, the model was also tested for different numbers of Quanvolutional layers (1, 4, 8, 16, 32) for 600 training images and 150 test images.

<img width="400" alt="Graph" src="https://user-images.githubusercontent.com/55295304/184308127-ec4cb769-3b37-4823-8ace-eb9517c3b149.png">

