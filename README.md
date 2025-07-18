# Eye-Controlled-Mouse

This project enables mouse control using only eye movements and blinks, leveraging computer vision and machine learning technologies. It is built using Python and the OpenCV, Dlib, and PyAutoGUI libraries to provide a hands-free experience for controlling the mouse cursor.

## 🚀 Features

- Cursor movement using eye direction
- Mouse click through eye blink detection
- Real-time face and eye tracking
- Lightweight and user-friendly

## 🧠 Technologies Used

- Python
- OpenCV
- Dlib
- PyAutoGUI
- Imutils

## 📂 Project Structure

```
Eye-Controlled-Mouse/
├── main.py                  # Main script to run the program
├── README.md                # Project documentation
├── shape_predictor_68_face_landmarks.dat  # Pretrained facial landmark model
```

## ⚙️ Requirements

Before running the project, make sure to install the following dependencies:

```bash
pip install opencv-python dlib imutils pyautogui
```

You also need to download the `shape_predictor_68_face_landmarks.dat` file from the [dlib model download page](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2), extract it, and place it in the root directory of the project.

## 🧪 How It Works

1. Detects the face and facial landmarks using Dlib.
2. Extracts eye regions and calculates the eye aspect ratio (EAR).
3. Uses EAR to detect blinks and determine gaze direction.
4. Moves the cursor and performs click actions based on the above data.

## 🖱️ Controls

- **Look Left / Right / Up / Down**: Move cursor
- **Blink**: Perform mouse click

## 📸 Screenshots

> Add screenshots here (optional for better visualization)

## 📌 Notes

- Ensure good lighting and clear visibility of your face.
- Webcam access is required.
- The project may require calibration for different lighting or camera angles.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Author

**Omkar Sutar**

GitHub: [Omkar-Sutar-exe](https://github.com/Omkar-Sutar-exe)

---

Feel free to contribute, open issues, or suggest improvements!

