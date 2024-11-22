# Deep Learning-Based Speaker Recognition System

This repository implements a speaker recognition system using a transformer-based deep learning model. The project focuses on classifying speakers based on input features derived from audio data.

**Features**

	•	Utilizes transformer architecture for speaker classification.
	•	Processes audio data by converting raw waveforms into mel-spectrograms.
	•	Efficiently segments mel-spectrograms for training and evaluation.

**Dataset**

The dataset contains audio samples from 600 speakers. The preprocessing involves:

	•	Converting raw waveforms into mel-spectrograms.
	•	Segmenting spectrograms to improve training efficiency.

**Data Source**

	•	Email: Drop me an email @tejasingampalli1@gmail.com for the dataset.
	•	Place the data in the data directory with the following structure:

 data/
├── train/
├── train_label.csv
├── test/
├── test_id.csv

**Prerequisites**

	•	Python 3.x
	•	Required libraries:
	•	TensorFlow/PyTorch (depending on the implementation)
	•	Librosa for audio processing
	•	NumPy, pandas, matplotlib

**Install the dependencies using:**

pip install -r requirements.txt


**Usage**

	1.	Preprocess the Dataset: Convert audio files into mel-spectrograms and segment them as needed.
	2.	Train the Model: Run the training script to train the transformer-based model.
	3.	Evaluate the Model: Use the test dataset to evaluate performance metrics.

**Notebook Execution**
	•	The provided Jupyter Notebook contains code for preprocessing, model training, and evaluation.
	•	Run the notebook in a compatible environment (e.g., Google Colab, Jupyter).

**Acknowledgments**

	•	Author: Teja Pavan Sai Singampalli

 
