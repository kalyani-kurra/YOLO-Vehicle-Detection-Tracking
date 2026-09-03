# YOLO Vehicle Detection, Tracking and Counting

## About the Project

This project uses **YOLOv8** to detect, track, and count vehicles from a video.

The project is implemented in **Google Colab using Python**.

## Technologies Used

* Python
* Google Colab
* YOLOv8
* Ultralytics
* OpenCV
* ByteTrack
* Pandas

## What I Did

1. Installed the required libraries.
2. Loaded the **YOLOv8 Nano (`yolov8n.pt`) pretrained model**.
3. Uploaded and read the input video.
4. Checked the video properties such as FPS, width, height, and total frames.
5. Tested YOLO detection on the first frame.
6. Selected vehicle classes:

   * Car
   * Motorcycle
   * Bus
   * Truck
7. Used **YOLO tracking with ByteTrack**.
8. Resized video frames and processed the video frame by frame.
9. Added bounding boxes, vehicle class names, and tracking IDs.
10. Created a counting line and counted vehicles when they crossed it.
11. Stored vehicle information such as **Track ID, Class, Confidence, and Frame Number** using Pandas.
12. Generated the final processed video.

## Project Files

```text
YOLO-Vehicle-Detection-Tracking/
│
├── YOLO_.ipynb
├── input_video.mp4
├── predicted_highway.mp4
└── README.md
```

## Output

The final output video is:

`predicted_highway.mp4`

It shows vehicle detection, tracking IDs, bounding boxes, counting line, and vehicle counting.

## Model

The project uses the **pretrained YOLOv8n model**. No custom model training was performed.


