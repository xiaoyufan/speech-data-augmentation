# Speech Data Augmentation

- [Speech Data Augmentation](#speech-data-augmentation)
  - [Development](#development)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Train the baseline model](#train-the-baseline-model)

## Development

### Prerequisites

- Linux or Mac environment (required by Mozilla's DeepSpeech)
- Python 3.6
- Jupyter notebook
- [Mozilla's DeepSpeech](https://github.com/mozilla/DeepSpeech)

### Setup

1. Download [Kaggle's TensorFlow Speech Recognition Challenge dataset](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data) and decompress it.

1. Folllow DeepSpeech's setup [instructions](https://deepspeech.readthedocs.io/en/v0.9.2/TRAINING.html#getting-the-training-code) on training a model.

1. Run `cp .env.example .env` and update the configurations per your settings.

### Train the baseline model

The baseline is established by training a DeepSpeech model with [Kaggle's TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge) [dataset](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data).

1. Run Jupyter notebook [train_baseline.ipynb](train_baseline.ipynb).

