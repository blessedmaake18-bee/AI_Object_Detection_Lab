## Steps to Run Object Detection

1. Create a project folder and place the following files inside:

   * `lab_1.py`
   * test image
   * test video

2. Open **Command Prompt (CMD)** and navigate to the project folder:

   ```
   cd Desktop\AI_Object_Detection_Lab
   ```

3. Install the required libraries:

   ```
   pip install ultralytics opencv-python
   ```

4. Open the `lab_1.py` script and set the source file for detection:

   Example for image detection:

   ```
   source = "test_image.jpg"
   ```

5. Run the script:

   ```
   python lab_1.py
   ```

6. The YOLOv8 model will load and detect objects in the image or video.
   Detected objects will appear with **bounding boxes and confidence scores**, and the output file will be saved automatically.
