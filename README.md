# Age and Gender Detection Using OpenCV
This project uses OpenCV's deep learning module (cv.dnn) to detect human faces in an image and classify their age and gender. The model is based on pre-trained Caffe networks.

### Features
1. Detects faces using OpenCV's DNN face detector
2. Predicts gender (Male / Female)
3. Estimates age in predefined age groups
4. Works on images with multiple faces

### Model Details
1. Face Detection: OpenCV’s DNN face detector (opencv_face_detector.pb)
2. Age Estimation: Caffe model (age_net.caffemodel)
3. Gender Classification: Caffe model (gender_net.caffemodel)
4. Predefined Age Groups: ['(0-2)', '(4-6)', '(8-12)', '(15-20)', '(25-32)', '(38-43)', '(48-53)', '(60-100)']

### Example Outputs

![image](https://github.com/user-attachments/assets/0f4e05b0-11cf-423f-8ed1-f106a272168c)

![image](https://github.com/user-attachments/assets/e87abe16-9dbc-4fdb-bbce-02590bfb1b62)

