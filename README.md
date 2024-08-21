# Human-Action-Recognition
Human Action Recognition Using CNN and LSTM 


# Overview
This project focuses on human action recognition using advanced deep learning techniques, specifically Convolutional LSTM (ConvLSTM) and Long-term Recurrent Convolutional Networks (LRCN). The goal is to accurately classify human actions in video sequences, leveraging both spatial and temporal features.

# Dataset
This project uses the UCF50 dataset, which is a popular benchmark dataset for human action recognition.

**Description:** The UCF50 dataset contains 50 action categories with a total of 6,618 videos. Each video is labeled with one of the 50 action categories, including actions like "Jumping Jack," "Walking," and "Running." The dataset covers a wide range of human actions and is diverse in terms of viewpoints and backgrounds.
**Organization:** The dataset is organized into directories where each directory corresponds to a specific action class. Each action directory contains several video files of that particular action.

# Libraries
Video Processing: `cv2`, `moviepy.editor`, `pafy`, `youtube-dl`, `pytube`
Data Manipulation: `numpy`, `datetime`, `collections.deque`
Machine Learning: `tensorflow`, `tensorflow.keras.layers`, `tensorflow.keras.models`
Utilities: `sklearn.model_selection.train_test_split`, `matplotlib.pyplot`, `tensorflow.keras.utils.to_categorical`, `tensorflow.keras.utils.plot_model`, `tensorflow.keras.callbacks.EarlyStopping`


# Approaches
## 1. Convolutional LSTM (ConvLSTM)
The ConvLSTM model integrates convolutional operations with LSTM units to capture both spatial and temporal information. This approach is well-suited for recognizing actions in video sequences by processing frames with spatial filters and then learning temporal dependencies.

**Architecture**: The ConvLSTM model consists of several ConvLSTM layers followed by fully connected layers for classification.

![image](https://github.com/user-attachments/assets/438957ff-61b9-4a29-93b6-cd116c94a6cc)


## 2. Long-term Recurrent Convolutional Networks (LRCN)
The LRCN model combines Convolutional Neural Networks (CNN) with LSTM networks. The CNN extracts spatial features from individual frames, and the LSTM captures temporal dependencies across frames.

**Architecture**: The LRCN model first applies CNN layers to each frame to obtain feature vectors, which are then fed into an LSTM network for action classification.


![image](https://github.com/user-attachments/assets/8d7d47aa-d389-48ec-b16c-73584c97e52f)

![image](https://github.com/user-attachments/assets/6fe4541d-1278-4f42-9437-e35463e65cd0)


