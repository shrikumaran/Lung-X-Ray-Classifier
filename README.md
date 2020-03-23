# Lung-X-Ray-Classifier
Classifies given X-Ray images of lungs into two classes, Normal lungs and lungs infected with Pneumonia

Chest X-ray images (anterior-posterior) of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou was collected.
https://data.mendeley.com/datasets/rscbjbr9sj/2

Trained the fully connected layers of a VGG19 model while freezing the Convulotional layers.
Used PyTorch to train the model.
Trained the whole model from scrath fro 25 epochs and got a Validation Accuracy of 84.6%.
Meanwhile training only the fully connected layers for 100 epochs got a Validation accuracy of 85.5%.


