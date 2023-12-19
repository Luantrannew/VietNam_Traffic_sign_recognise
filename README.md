**Traffic Sign Detection with YOLOv5 using Google Colab GPU (T4)**
This repository implements a traffic sign detection model using the YOLOv5 object detection architecture on Google Colab with a T4 GPU.
---------------------------------------------------------------

**Overview**
Traffic sign detection is an important computer vision task for autonomous driving and advanced driver assistance systems. This repository focuses on detecting and classifying traffic signs from images and video frames recorded in Da Nang city, Vietnam.
The model is built using the state-of-the-art YOLOv5s detection framework, which offers excellent accuracy and speed for real-time applications. The network backbone and model parameters have been customized for optimized traffic sign detection performance.

**Model Architecture and Training**
The YOLOv5s variant is used as the base model and pre-trained weights.
The model is trained on the Vietnam Roboflow traffic sign dataset consisting of over 4,200 images across 58 sign classes (https://universe.roboflow.com/vietnam-traffic-sign-detection/vietnam-traffic-sign-detection-2i2j8/dataset/6/download) . We added and labeled one more class R.403.
Training is done for 100 epochs with a batch size of 16 in the second time and worked just fine

**Inference and Results**
For inference, the model takes as input test images in the test folder or video frames recorded in Da Nang, Vietnam and outputs the detected sign bounding boxes, class labels and detection confidence scores.
Achieves strong performance detecting and classifying traffic signs across 58+ classes in real-time.

<img width="368" alt="image" src="https://github.com/Luantrannew/VietNam_Traffic_sign_recognise/assets/62492632/e1085822-9196-4f44-8a52-13561d32b25f">

