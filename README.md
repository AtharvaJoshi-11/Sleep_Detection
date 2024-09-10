# Sleep State Detection

## Overview

This project focuses on sleep onset and wake-up detection using a wrist-worn accelerometer. A Deep-GRU (Gated Recurrent Unit) architecture with multihead attention is employed to train the data. The model is trained on data from approximately 280 patients, with each patient being recorded for around 23 nights. The independent variables used as input to the time series data are the 'anglez' and 'enmo'.

## Dataset

![Image Alt text](/sleep_train_events.csv_dataset.JPG)



## Model Architecture

![Image Alt text](/deep_gru.jpg)
