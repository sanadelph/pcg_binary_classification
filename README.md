# pcg_binary_classification
Heart sound classification plays a critical role in the early diagnosis of cardiovascular diseases. phonocardiography is a diagnostic technique that creates a  graphic record, or phonocardiogram, of the sounds and murmurs produced by the contracting heart, including its valves and associated great vessels  Following the recent advancements in technology as well as the various fields of pattern recognition and classification and machine learning, efforts have been made to automate the analysis of PCG signals in a non-invasive manner.
The dataset can be downloaded from https://physionet.org/content/challenge-2016/1.0.0/. In this dataset,6 training databases are provided, containing a total of 3,240 heart sound recordings collected from a variety of sources. In some cases, a simultaneous ECG signal is also provided. Each subject has been classified as either “normal” or “abnormal” (typically diagnosed with coronary artery disease or heart valve defects), and each record is separately annotated as having “good” or “poor” signal quality. 
This work proposes a novel method for the task of classifying heart sounds into "normal" and "abnormal" classes using LSTM deep learning model. the hyperparameters of this model were tuned and optimized by means of genetic algorithm. The features of heart sounds were extracted using MFCC.

# Required Packages
The project is developed using Python 3 environment and following packages are used in the notebook provided:
- Keras and Tensorflow
- [DEAP](https://github.com/DEAP/deap)
- Numpy
- Pandas
