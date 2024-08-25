# LipNet
A simple deep learning model that is able to perform lip reading. The notebook file `LipNet.ipynb` can be easily retrained to adapt to new datasets or different scenarios. The `app/` directory contains all the files needed for deploying the model as a web application using Streamlit.

<img src="https://github.com/user-attachments/assets/819a8997-90cc-4431-b6c2-1826a404cef6" alt="image" width="400" height="200">

## Dataset & Model

The `data/` directory contains the entire dataset for 1,000 sentences from one speaker. The structure is as follows:

- `data/alignments/s1`: Contains the annotations.
- `data/s1`: Contains the video files.

The model has been trained up to checkpoint 74 epochs. You can download the trained model from [model checkpoint 74](https://www.kaggle.com/models/ankurchanda/lipnet-model-checkpoint-74)

## References

Based on results from [LipNet: End-to-End Sentence-level Lipreading.](https://arxiv.org/abs/1611.01599)
