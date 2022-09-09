Live Action Detection Using MediaPipe Holistic and LSTM

Abstract:

This paper explores the efficiency of the MediaPipe Holistic framework for extracting a fast and accurate perception of human actions, poses, face landmarks and hand movements on a set of images taken in real-time through the web camera, which is accessed through OpenCV. LSTM is used for modelling in combination with a few Dense layers. Programming is done with Python and the internal performance measures obtained are visualized for comparison and discussion. In addition to that, real-time testing is also done for all trained actions through the web camera with people of different ages and gender.

Of the five senses, vision is undoubtedly the one man depends on most, since visual interpretation is the easiest to carry out. The visual system is the efficient one which provides maximum data he receives for processing with a data rate usually exceeding 10Mbps. Computer vision enables a digital systems that can process, analyse, and make sense of visual data like images or videos, in the same way that humans do. Pose estimation or human action recognition is a popular task in Computer Vision which explores how to digitally remember the basic human actions by exploring the locations and moves of human skeletal joints using the easiest hardware like an RGB camera. Live action  has various real-life applications like sign language recognition, emotion detection, human posture analysis etc.

This work focuses on predicting three human actions ("Hello”, “Thank You", and "I Love You") from a live video, by analyzing the body, face and hand movements from a stream of image frames. The author used LTSM (Long Short-Term Memory) with a few Dense layers for training the model. ‘MediaPipe-Holistic’ is the framework used for data preparation to extract the key points from training data.


