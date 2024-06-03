# object-detection

The project can be considered an extension of image classification. It automatically detects and marks the coordinates of hats in 'real time' using your laptop's webcam . We utilized the YOLOv8. In for some parts google colab was used.
Summary of points:
● Imported necessary modules and mounted Google Drive in the Colab
environment for file access.
● Installed the "ultralytics" library for YOLO object detection.
● images were obtained via the laptop webcam
● Labeled images into "No hats" and "Hats" categories, with 100 images per label.
● Label studio was using to create bounding boxes on all images
● Created an instance of the YOLO model using pre-trained weights.
● confusion matrix and training results images were obtained.
● Ran YOLO object detection on the validation dataset using the trained model.
● Copied the trained model from "/content/runs" directory to Google Drive for storage.
● Created a model path and established a threshold of 0.5.
● Called the webcam and initiated real-time recording.
