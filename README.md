 Fashion Clothes Try On Report

Introduction
In this report, we explore the application of high-resolution virtual image try-on (HR Viton) using a pretrained model, Detectron2 for human body part detection, and Graphonomy for universal human parsing. The objective is to understand the capabilities and limitations of these models for the task of fashion clothes try-on. This experiment is conducted using a dataset obtained from these models.


 Model Utilization
1. HR Viton: HR Viton is employed to facilitate virtual clothing try-on. This pretrained model allows the overlay of clothing items onto an image of a person.

2. Detectron2: Detectron2 is used to identify different parts of the image, specifically the human body and its features. This aids in correctly aligning clothing with the body.

3. Graphonomy: The Graphonomy model is used for universal human parsing through graph transfer learning, which assists in the identification of different parts of the body for precise clothing placement.

 Dataset
The dataset used in this experiment is collected from the output of these models, containing high-resolution images of both clothing and human subjects.

 Observations
1. Image Quality and Background: The quality of the input images is crucial. Both the clothing image and the image of the human subject must be clear and free of background interference. Images with complex backgrounds may lead to incorrect placements of clothing.

2. Poses: The performance of the model is significantly influenced by the pose of the human subject. While certain poses produce accurate try-on results, others may not align the clothing correctly.

3. Image Size and Resolution: For the best output, it is essential that both the input images (clothing and human) have the same size and resolution. Mismatched sizes can lead to misalignment issues.

 Conclusion
In conclusion, the HR Viton model, supported by Detectron2 and Graphonomy for human body parsing, provides good output for the task of virtual clothing try-on. However, this output is contingent on certain constraints. The quality and clarity of input images, appropriate poses, and matching image sizes and resolutions are critical factors that influence the performance of the models. When these constraints are met, the models demonstrate their capability in enhancing the virtual try-on experience.


