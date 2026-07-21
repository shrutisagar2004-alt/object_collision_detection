A MATLAB-based computer vision application that detects vehicles in images and videos using the pre-trained YOLOv4 object detector. The system identifies the nearest vehicle in the driving lane, estimates the distance between vehicles, and provides a real-time collision warning to improve road safety.

📌 Features
Detects vehicles using the pre-trained YOLOv4 (COCO) model.
Supports images and videos as input.
Filters relevant vehicle classes (Car, Bus, Truck, Motorbike).
Identifies the nearest vehicle in the current driving lane.
Estimates the distance between the ego vehicle and the detected vehicle.
Generates SAFE or DANGER alerts based on a collision threshold.
Displays vehicle bounding boxes, estimated distance, and collision status in real time.
🛠️ Technologies Used
MATLAB
Computer Vision Toolbox
Deep Learning Toolbox
YOLOv4 Object Detector
CSP-DarkNet53 (COCO Pre-trained Model)
⚙️ Working
Select an input image or video.
Load the pre-trained YOLOv4 object detector.
Detect vehicles in each frame.
Filter vehicles located within the driving lane.
Identify the nearest vehicle.
Estimate the gap distance using bounding box dimensions.
Compare the estimated distance with a predefined safety threshold.
Display the detection results with SAFE or DANGER status.
📂 Input
JPG
PNG
JPEG
MP4
AVI
📤 Output
Vehicle detection with bounding boxes.
Distance estimation to the nearest vehicle.
Lane-based front vehicle selection.
Real-time collision warning.
Annotated image or video with detection results.
🚀 Future Enhancements
Real-time webcam support with optimized performance.
Accurate depth estimation using stereo vision or LiDAR.
Lane detection integration.
Vehicle speed estimation and Time-to-Collision (TTC) calculation.
Support for pedestrian and cyclist collision detection.
📷 Sample Output
Vehicle detection with highlighted bounding boxes.
Estimated gap distance in meters.
SAFE (Green) or DANGER (Red) collision alert.
