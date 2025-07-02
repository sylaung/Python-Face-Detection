# Face Detection with OpenCV (Python)

Python script to detect faces in an image using Haar cascades with OpenCV.

## Usage

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Place your input image in the project folder as `test.jpg`.

3. Run the script:
   ```
   python app.py
   ```

4. A window will display the detected face(s), and a new image `face_detected.jpg` will be saved with bounding boxes.

## Files

- `app.py` — Main detection script  
- `haarcascade_frontalface_default.xml` — Pre-trained Haar model from OpenCV  
- `test.jpg` — Input image (replace with your own if needed)  
- `face_detected.jpg` — Output with face box(es)
