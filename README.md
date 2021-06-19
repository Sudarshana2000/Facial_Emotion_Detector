# Facial_Emotion_Detector

Detects the following facial emotions - angry, disgust, fear, happy, sad, surprise, neutral - using fer2013 datasets with a keras CNN model and openCV.
Accuracy: 66%

## Requirements

- python 3
- cv2
- Tensorflow 2

Download [pre-trained emotion detection model](https://github.com/oarriaga/face_classification/blob/master/trained_models/emotion_models/fer2013_mini_XCEPTION.102-0.66.hdf5), [caffemodel](https://github.com/sr6033/face-detection-with-OpenCV-and-DNN/raw/master/res10_300x300_ssd_iter_140000.caffemodel) and [prototxt](https://github.com/sr6033/face-detection-with-OpenCV-and-DNN/blob/master/deploy.prototxt.txt) in [models](./models/) for model inferences.

## Usage

To get results in images, use

```
facial_emotion.process(image_path)
```

To get results in real-time and in video feeds, use

```
facial_emotion.real_time_feed(video_path)
```

# Result

<img src="https://github.com/Sudarshana2000/Facial_Emotion_Detector/blob/master/sample.png" />
<br />
