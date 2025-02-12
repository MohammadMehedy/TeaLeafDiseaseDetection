# Tea Leaf Disease Detection Using YOLOv8, YOLOv5, and Faster R-CNN

### Overview
This project aims to detect various diseases in tea leaves using deep learning models such as YOLOv8, YOLOv5, and Faster R-CNN. The system detects diseases in live images of tea leaves and provides treatment suggestions. The dataset used in this project includes images of tea leaves with 8 types of diseases, collected from the Bangladesh Tea Research Institute (BTRI) in Sylhet.

### Dataset
The dataset contains images of tea leaves labeled with the following 8 diseases:

 Algal Leaf Rust<br>
 Bug Eaten<br>
 Healthy<br>
 Leaf Blight<br>
 Leaf Spot<br>
 Nutrition Deficiency<br>
 Red Spider Mite<br>
 Tea Mosquito Bug<br>
 The dataset was collected from the Bangladesh Tea Research Institute (BTRI) in Sylhet.

### Features
Disease Detection: Detects diseases in tea leaves using deep learning models.<br>
Live Image Detection: The model can detect diseases from live images.<br>
Treatment Suggestions: After detection, the app suggests possible treatments for the identified diseases.<br>
Multiple Models: The project uses YOLOv8, YOLOv5, and Faster R-CNN for comparison and performance evaluation.

### Technologies Used
YOLOv8: For real-time object detection and disease classification.<br>
YOLOv5: Another object detection model used for disease classification.<br>
Faster R-CNN: A region-based object detection model used for comparison.<br>
Python: The programming language for model training and app development.<br>
TensorFlow/PyTorch: Frameworks used for training the models.<br>
OpenCV: For image processing and handling live image inputs.<br>
Android Studio: For building the mobile application for disease detection and treatment suggestions.

### Running the Detection App
Open the Android app project in Android Studio.<br>
Build and run the app on your Android device or emulator.<br>
The app uses the trained model to detect diseases in live images from the camera and provides treatment suggestions.<br>

### Usage
Live Detection: Open the app and allow it to access the camera. The model will detect diseases from the tea leaf in real-time and provide a treatment recommendation.<br>
Model Evaluation: You can evaluate the models' performance by running the testing scripts for each model:<br>
bash<br>
python test_yolov8.py<br>
python test_yolov5.py<br>
python test_faster_rcnn.py<br>

### Contributions
Feel free to contribute by opening issues or submitting pull requests. Suggestions for improving the detection system or adding more diseases are welcome!

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements
Bangladesh Tea Research Institute (BTRI) for providing the dataset.<br>
YOLOv8, YOLOv5, and Faster R-CNN developers for their model frameworks.<br>
TensorFlow/PyTorch communities.<br>
OpenCV contributors.<br>
