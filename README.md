## Functionality Supported

-   Admin and Employee Login
-   Admin : Register new employees.
-   Admin : Add employee photos to the training dataset.
-   Admin: Train the model.
-   Admin: View attendance reports of all employees. Attendance can be filtered by date or employee.
-   Employee - View attendance reports of self.

## Building Using

-   **OpenCV** - Open Source Computer Vision and Machine Learning software library
-   **Dlib** - C++ Library containing Machine Learning Algorithms
-   **face_recognition** by Adam Geitgey
-   **Django**- Python framework for web development.

### Face Detection

-   Dlib's HOG facial detector.

### Facial Landmark Detection

-   Dlib's 68 point shape predictor

### Extraction of Facial Embeddings

-   face_recognition by Adam Geitgey

### Classification of Unknown Embedding

-   using a Linear Support Vector Machine (scikit-learn)
