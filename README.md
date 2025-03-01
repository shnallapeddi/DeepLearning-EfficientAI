## Title: Efficient AI: Bridging the Gap with Knowledge Distillation Techniques
#### Summary: Here, we train a teacher (a larger CNN) and a student (a smaller CNN) on the CIFAR-10 image classification dataset, focusing on Knowledge Distillation to transfer the teacher’s learned patterns to the student. After loading and preprocessing CIFAR-10, we train and evaluate the teacher model to establish a high baseline accuracy. We then train the student in two ways—first, a simple supervised approach, and second, with distillation, which combines a soft-target loss (from the teacher’s predictions) and a ground-truth label loss. This approach helps the student model achieve higher accuracy than it would through standard training alone, illustrating that, even with fewer parameters, a distilled student can closely match the teacher’s performance.

Please refer to the table regarding the uploaded files below.

| **File Name**                                  | **Contents**                                                          | **Description**                                                                                                                                                                                     |
|------------------------------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Efficient_AI_snallape_50593866.ipynb**  | Jupyter Notebook (Python code) implementing Knowledge Distillation on the CIFAR-10 dataset | Contains data loading, model definitions (teacher & student), training routines, and evaluation metrics. Demonstrates how a smaller model can learn from a larger teacher model via distillation, tracking accuracy and losses.            |
| **Efficient_AI_snallape_50593866.pdf**         | PDF report describing the concept, methodology, and results of the distillation experiments  | Discusses the theoretical background of Knowledge Distillation, experiment setup, hyperparameter choices, and performance comparisons. Includes a summary of the observed improvements and conclusions drawn from the results.           |


