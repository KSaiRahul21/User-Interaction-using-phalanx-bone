# Enhancing User Interaction with Phalanx Detection using CNNs

Touchscreens are the most successful input method for smartphones. Despite their flexibility, touch input is limited to the location of taps and gestures. We present Phalanx Touch, an additional input modality that differentiates between touches of fingers and the phalanx. We present a use case for Phalanx Touch, including the use as a shortcut to open an application (for instance camera). To evaluate the use case, we have developed a model that differentiates between finger and phalanx touch with an accuracy of 98% in realistic scenarios. Results of the evaluation show that participants perceive the input modality as intuitive and natural to perform.

The code files are arranged as follows:

1) 01_Import_data.ipynb : Importing capacitive touch data obtained from Android Smart phone and saving in data frames.
2) 02_Data_pre-processing_and_augmentation.ipynb : Performs blob detection to obtain touches and augmentation to increase the data set.
3) 03_Input_for_NN.ipynb : Data cleaning and labelling to prepare data for training.
4) 04_CNN_network.ipynb  : The CNN network used for training to classify finger and phalanx bone touches.
5) 05_Model_export.ipynb : Exporting the trained network by freezing the graphs to Android smartphone to test the use-cases.

