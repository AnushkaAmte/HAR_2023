# HAR: Human Activity Recognition
This project envisions a system that can be used for two use cases: Fight
Detection on Campus and Drowsy Driver Detection. The scope of our
current project is limited to detecting small fights occurring in campus and
alerting the driver when they start to feel drowsy. We limit our current
applications to a single camera usually remote, which needs to be connected
to our application and inference models. We propose a website hosted on
a server to streamline this process.

# LRCN:
RCN (Long-term Recurrent Convolutional Networks) combines CNNs
and RNNs to recognize human activities in videos. LRCN first extracts
visual features from each frame of the input video using CNNs and then
processes these features with an RNN, such as an LSTM or GRU, to cap-
ture the temporal dynamics. The RNN component allows LRCN to model
long-term dependencies between frames, which is crucial for activity recog-
nition. By integrating CNNs and RNNs, LRCN can predict activity labels
for each video segment and localize the temporal boundaries of the activ-
ity. 
![alt text](image.jpg)
# Requirements

- Flask 2.2.3 and above
- PyQt5 5.15.1 and above
- OpenCV 3 or 4
- Tensorflow 2.11 and above
- CUDNN 8.4 and above
- CUDA 11.1 and above

# Demo:
Drowsy Driver Detection
![alt text](image.jpg)
Fight Detection
![alt text](image.jpg)
