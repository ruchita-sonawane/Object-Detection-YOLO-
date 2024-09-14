# Object Detection Using YOLO<br>
This project is a Python application that utilizes YOLOv8 (You Only Look Once) for real-time object detection in video feeds.<br> By leveraging the power of OpenCV and the ultralytics YOLO model, the project identifies objects in each frame with high accuracy and efficiency. <br>The system draws bounding boxes and labels around detected objects, making it ideal for tracking multiple objects in dynamic scenes.
<br>
<br>Key Features:<br>
<br>Real-Time Video Processing: Captures video from a file and processes each frame to detect objects in real-time.
<br>YOLOv8 Object Detection: Employs the YOLOv8 model to detect a wide variety of objects with precise bounding boxes.
<br>Dynamic Object Tracking: Continuously tracks detected objects throughout the video, ensuring seamless detection across frames.
<br>Confidence Filtering: Only displays objects detected with a confidence level above 40%, ensuring reliable detection results.
<br>Class-Based Coloring: Uses different colors for different object classes, enhancing the visual distinction between detected objects.
<br><br>Implementation Details:<br>
<br>Video Capture: Video is loaded using OpenCV’s VideoCapture from a specified file path.
<br>Object Detection: YOLOv8 is applied to each frame for object detection, with bounding boxes drawn around objects of interest.
<br>Class Colors: Each detected class is assigned a unique color for better visualization.
<br>Bounding Boxes: Rectangles are drawn around detected objects, and class names along with confidence scores are displayed on the video feed.
<br>Colab Compatibility: Includes cv2_imshow for displaying video frames in Google Colab.
<br><br>File Structure:
<br>main.py:<br> The main script containing the YOLO-based object detection implementation.
<br><br>Requirements:<br>
<br>Python 3.x
<br>OpenCV
<br>ultralytics
<br><br>Running the Project:<br>
<br>Install the required libraries using pip install opencv-python ultralytics.<br>
Load your video file by specifying the path in the script.<br>
Run the script to start detecting objects in the video.<br>
<br>This project offers a powerful and flexible way to detect and track objects in video feeds. It can be further enhanced by adding features such as real-time webcam input, multiple object tracking algorithms, or saving detection results.
<br><br>
Feel free to explore and customize the project to fit your specific requirements!
