# Human-Action-Recognition
Human Action Recognition Using CNN and LSTM 


# Overview
This project focuses on human action recognition using advanced deep learning techniques, specifically Convolutional LSTM (ConvLSTM) and Long-term Recurrent Convolutional Networks (LRCN). The goal is to accurately classify human actions in video sequences, leveraging both spatial and temporal features.

## Approaches
# Convolutional LSTM (ConvLSTM)
The ConvLSTM model integrates convolutional operations with LSTM units to capture both spatial and temporal information. This approach is well-suited for recognizing actions in video sequences by processing frames with spatial filters and then learning temporal dependencies.

**Architecture**: The ConvLSTM model consists of several ConvLSTM layers followed by fully connected layers for classification.

# Long-term Recurrent Convolutional Networks (LRCN)
The LRCN model combines Convolutional Neural Networks (CNN) with LSTM networks. The CNN extracts spatial features from individual frames, and the LSTM captures temporal dependencies across frames.

**Architecture**: The LRCN model first applies CNN layers to each frame to obtain feature vectors, which are then fed into an LSTM network for action classification.
