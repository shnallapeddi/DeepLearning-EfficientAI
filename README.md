## Title: Efficient AI: Bridging the Gap with Knowledge Distillation Techniques
#### Summary: Here, we train a teacher (a larger CNN) and a student (a smaller CNN) on the CIFAR-10 image classification dataset, focusing on Knowledge Distillation to transfer the teacher’s learned patterns to the student. After loading and preprocessing CIFAR-10, we train and evaluate the teacher model to establish a high baseline accuracy. We then train the student in two ways—first, a simple supervised approach, and second, with distillation, which combines a soft-target loss (from the teacher’s predictions) and a ground-truth label loss. This approach helps the student model achieve higher accuracy than it would through standard training alone, illustrating that, even with fewer parameters, a distilled student can closely match the teacher’s performance.

Please refer to the table regarding the uploaded files below.

<img width="745" alt="image" src="https://github.com/user-attachments/assets/955c0711-1603-4961-a3fc-2027abc21aff" />
