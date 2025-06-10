
# CIFAR-10 Model Comparison Report
This report summarizes the training results, challenges, and insights from training various deep learning models on the CIFAR-10 dataset.

Challenges Encountered
- A huge amount of time to run each epoch in case of vggs and alexnet
- Overfitting in ANN and shallow CNNs
- Underfitting in ANN (poor accuracy)
- Input size mismatch when using pretrained models (required 224x224)


SOME INSIGHTS
- Transfer Learning significantly boosts performance and reduces training time.
- Data augmentation helps prevent overfitting and improves generalization.
- Monitoring validation loss and accuracy helps guide training duration.

Observations:
- On increasing the layer of ann and increasing no of epochs to a higher number the models accuracy decreased as model became overfit.
- Used dropouts in cnn to prevent overfitting
