# Personal Protective Equipment (PPE) Detection to Maintain Construction Site Safety!
Many risks are encountered while workers are in the hazardous realities of construction that may lead to deaths and severe indusries.Accordingly,existing deep learning-based models for personal protective equipment (PPE) detection can detect limited types of PPE. This paper presents an approach to training and evaluating a deep learning-based framework using the You Only Look Once (YOLO) architecture for the detection and classification of six classes, including person, vest, and helmets with four colors. A custom dataset of CHV was created, consisting of 1330 images. With preprocessing and optimization applied, the dataset was trained on a pre-trained YOLO model and used Roboflow to reformulate it to YOLOv5 format. The model was trained with differing batch sizes and epoch values, and this paper compares mAP results with these differences. In contrast, the color space adjustment augmentation techniques were implemented automatically by the YOLOv5 model. The Experimental results that were attained in this work show valuable results with the YOLOv5 model as it attained an mAP of 84.2%. This proves the power of the YOLOv5 algorithm in PPE detection.
