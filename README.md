 Object Detection and Tracking

1. What is this project?
This project detects objects in a video and tracks their movement. I developed it using Python and YOLOv8.

2. Why did I build this project?
I built this project to learn how object detection and tracking work in real-world applications.

3. What can this project do?
It can detect objects in uploaded videos, track their movement, show tracking IDs, and generate a processed video.

4. Which technologies did I use?
- Python
- YOLOv8
- OpenCV
- Streamlit
- ByteTrack

5. How does it work?
First, I upload a video. The application reads it frame by frame. YOLOv8 detects objects, and ByteTrack tracks them across frames. Finally, the application generates the processed video.

6. How can someone run this project?
First, install the required libraries using:

`pip install -r requirements.txt`

Then run:

`python -m streamlit run app2.py`

7. What did I learn from this project?
I learned how to work with video frames, use a pretrained YOLO model, detect objects, and track multiple objects in a video.

8. What is the main objective?
My main objective was to gain practical experience in computer vision and understand how AI can identify and track objects.

9. Who developed this project?
**Developer:** Burri Srinu

**Internship:** CodeAlpha AI Internship
