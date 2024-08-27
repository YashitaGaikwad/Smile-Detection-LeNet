# Smile-Detection-LeNet
Smile Detection using LeNet: A real-time smile detection system using the LeNet CNN architecture. This project explores model optimizations, including class balancing and the impact of batch normalization. Ideal for applications in customer service, healthcare, and emotion-driven technologies.

Introduction

Smile detection is a fascinating application of computer vision, with potential uses in customer service, retail, healthcare, and more. This project is inspired by the work of Balaji Srinivasan and CampusX on YouTube. The project aims to build a robust smile detection model while experimenting with different training strategies and model architectures.

Training Results

Epoch 15/15:
Accuracy: 95.7% /
Loss: 0.1176 /
Validation Accuracy: 91.04% /
Validation Loss: 0.2624

Key Learnings

Resource Constraints: Encountered memory issues due to a large dataset, which were resolved by converting the data type and using a data generator.
Model Complexity: Found that VGG16 was too complex and time-consuming, leading to a switch to LeNet, which was more efficient and performed better.
Data Handling: The model performed better without shuffling the training data.

Real-Life Applications

This smile detection model has potential applications in customer service, retail, and healthcare. It's even used in innovative ways, such as cafes where the door opens only when customers smile, enhancing the overall experience.

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
