# work-project-1
Cotton Disease Classification with CNNs

What it is: A deep learning project that classifies cotton images into four classes: diseased leaf, diseased plant, fresh leaf and fresh plant. It compares four architectures and uses explainable AI to interpret the results.

Method:

Models: A baseline CNN (128×128 inputs) and three transfer-learning models (VGG16, ResNet50 and EfficientNetB0, 224×224 inputs, pretrained on ImageNet, then fine-tuned).
Preprocessing: Pixel normalisation, one-hot labels, and augmentation (rotation, zoom, shear, flips).
Training: Adam optimiser, categorical cross-entropy, early stopping, checkpointing and learning-rate scheduling.
Explainability: LIME visualisations show that the models focus on disease spots and discolouration rather than background.

Results (test accuracy): Baseline CNN 94.3%, ResNet 96.2%, EfficientNet 96.2% (highest validation accuracy, 99.2%), VGGNet 98.1% (best test accuracy and most balanced).

Contents: Four notebooks (one per model), the full project report (PDF) and a link to the Kaggle dataset.

Skills shown: CNNs, transfer learning and fine-tuning, model comparison, XAI (LIME), TensorFlow/Keras.
