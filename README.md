# IIIT Hyderabad Speaker Recognition Model

This project presents a speaker recognition model developed as part of research conducted at IIIT in speech analysis. The model achieves an impressive accuracy of 94%, showcasing its efficacy in accurately identifying speakers from audio recordings. Leveraging state-of-the-art machine learning techniques and deep neural networks, the model demonstrates robust performance across various speech samples.

## Overview

This speaker recognition model is designed to contribute to advancements in speech analysis and bolster research efforts in the field. Through rigorous experimentation and fine-tuning, the model has been optimized to deliver reliable results, making it a valuable asset for applications requiring speaker identification, such as security systems, voice assistants, and forensic analysis.

## Dataset

The dataset used for training and evaluation is sourced from Kaggle. It contains speeches of five prominent leaders, namely:

- Benjamin Netanyahu
- Jens Stoltenberg
- Julia Gillard
- Margaret Thatcher
- Nelson Mandela

Each speaker's speeches are stored in separate folders with the respective names. Each audio file in the folder represents one second of speech, sampled at 16000 Hz and encoded in PCM format.

The original speeches for each speaker were single lengthy audio files, which have been chunked into one-second segments for easier workability. Combining the chunked audios from 0.wav to 1500.wav forms a complete speech of the respective speaker.

Additionally, there is a folder called background_noise containing audio clips that are not speeches but represent ambient sounds found inside and around the speaker environment, such as audience laughing or clapping. These can be mixed with the speeches during training for a more realistic environment.

The dataset details can be found at Kaggle Dataset (https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset).
