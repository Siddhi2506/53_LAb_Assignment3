## Car Detection Application using YOLOv8

This application demonstrates the use of the YOLOv8 object detection model for detecting cars in images. It follows these key steps:

**1. Environment Setup:**
- Installs necessary libraries, including `ultralytics` for YOLOv8.
- Sets the device to use ('cuda' for GPU if available, otherwise 'cpu').

**2. Dataset Preparation:**
- Assumes a dataset in YOLOv8 format is provided in a zip file.
- Extracts the dataset to a specified directory.

**3. Model Training:**
- Loads a pre-trained YOLOv8 nano model (`yolov8n.pt`).
- Trains the model on the custom car dataset for a specified number of epochs, image size, and device.

**4. Inference and Evaluation:**
- Locates and prints the path to the best trained model weights.
- Validates the model using the validation set and prints metrics (mAP50-95, Precision, Recall, F1 Score).
- Performs inference on test images and saves the results.

**5. Visualization:**
- Loads the trained model.
- Predicts on a specified test image.
- Visualizes the predictions by drawing bounding boxes and labels on the image.

**Discussion and Conclusion:**
- Provides space for discussing the achieved performance metrics and potential improvements.
- Concludes the lab experiment and highlights the learning outcomes.

**Usage:**
1. Ensure the necessary libraries are installed (`pip install ultralytics`).
2. Prepare your dataset in YOLOv8 format.
3. Update the paths in the code to match your dataset location and desired output directory.
4. Run the code cells in order to train, evaluate, and visualize the car detection results.

**Note:** This application assumes a basic understanding of YOLOv8 and object detection concepts. Refer to the Ultralytics documentation for detailed information.
