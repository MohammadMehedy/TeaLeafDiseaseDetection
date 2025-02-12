# Tea Leaf Disease Detection Using YOLOv8, YOLOv5, and Faster R-CNN

### Overview
This project aims to detect various diseases in tea leaves using deep learning models such as YOLOv8, YOLOv5, and Faster R-CNN. The system detects diseases in live images of tea leaves and provides treatment suggestions. The dataset used in this project includes images of tea leaves with 8 types of diseases, collected from the Bangladesh Tea Research Institute (BTRI) in Sylhet.

### Dataset
The dataset contains images of tea leaves labeled with the following 8 diseases:

Algal Leaf Rust
Bug Eaten
Healthy
Leaf Blight
Leaf Spot
Nutrition Deficiency
Red Spider Mite
Tea Mosquito Bug
The dataset was collected from the Bangladesh Tea Research Institute (BTRI) in Sylhet.

### Features
Disease Detection: Detects diseases in tea leaves using deep learning models.
Live Image Detection: The model can detect diseases from live images.
Treatment Suggestions: After detection, the app suggests possible treatments for the identified diseases.
Multiple Models: The project uses YOLOv8, YOLOv5, and Faster R-CNN for comparison and performance evaluation.

### Technologies Used
YOLOv8: For real-time object detection and disease classification.
YOLOv5: Another object detection model used for disease classification.
Faster R-CNN: A region-based object detection model used for comparison.
Python: The programming language for model training and app development.
TensorFlow/PyTorch: Frameworks used for training the models.
OpenCV: For image processing and handling live image inputs.
Android Studio: For building the mobile application for disease detection and treatment suggestions.

### Running the Detection App
Open the Android app project in Android Studio.
Build and run the app on your Android device or emulator.
The app uses the trained model to detect diseases in live images from the camera and provides treatment suggestions.

### Usage
Live Detection: Open the app and allow it to access the camera. The model will detect diseases from the tea leaf in real-time and provide a treatment recommendation.
Model Evaluation: You can evaluate the models' performance by running the testing scripts for each model:
bash
python test_yolov8.py
python test_yolov5.py
python test_faster_rcnn.py

### Contributions
Feel free to contribute by opening issues or submitting pull requests. Suggestions for improving the detection system or adding more diseases are welcome!

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements
Bangladesh Tea Research Institute (BTRI) for providing the dataset.
YOLOv8, YOLOv5, and Faster R-CNN developers for their model frameworks.
TensorFlow/PyTorch communities.
OpenCV contributors.
