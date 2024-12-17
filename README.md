# SurfaceCrackDetection

This project focuses on developing an automated system for
classifying concrete surface images into two categories:
cracked and non-cracked. Utilizing a Convolutional Neural
Network (CNN), the model is trained on a labeled dataset
containing images of both types. Data augmentation
techniques are applied to enhance model robustness, and the
test dataset is used to evaluate its predictive performance.
The output includes predictions saved in a structured CSV file.
This approach demonstrates the application of deep learning
to address real-world challenges in infrastructure
maintenance, offering improved efficiency and reliability
compared to manual methods.

Model Performance:
The CNN model
demonstrated excellent
performance in classifying
images of concrete surfaces.
Final Training Accuracy:
Batch Size 32: 99.76%
Batch Size 64: 99.73%

Training Time:
Training times for 10 epochs
were reasonable given the
complexity of the task:
Batch Size 32: 560.16
seconds (~9 minutes).
Batch Size 64: 521.71
seconds (~8.7 minutes).
The model trained slightly faster
with a larger batch size due to
fewer iterations per epoch.



The project successfully demonstrated the application of deep
learning for automated concrete crack detection. By utilizing a
Convolutional Neural Network (CNN), the model achieved high training
accuracy, with results of 99.76% (batch size 32) and 99.73% (batch
size 64), showcasing its ability to distinguish between cracked and
non-cracked surfaces effectively. The automated classification
significantly reduces human effort and offers a scalable solution for
structural inspections.
