# Car Scratch and Dents Detection using YOLONAS_l

## Introduction

This repository contains code for training a Car Damage Detection model using YOLOv5. The model identifies scratches and dents, drawing bounding boxes around them.

The dataset for this project can be downloaded [here](https://www.kaggle.com/datasets/lplenka/coco-car-damage-detection-dataset).

The source code for training is available in the `.ipynb` notebook, and the trained model weights (checkpoint files) are available in the `checkpoints` folder.

## Setting Up

### Environment Setup

1. Create a new Python/Anaconda environment.

2. Install the necessary packages:

    ```bash
    conda install numpy pandas matplotlib opencv cython jupyter
    ```

    - If you have a supported GPU, run:

      ```bash
      conda install torch torchvision torchaudio cudatoolkit=10.2 -c pytorch
      ```

    - If you don't have a supported GPU or want to train on a CPU, run:

      ```bash
      conda install torch torchvision torchaudio cpuonly -c pytorch
      ```

### Dataset Setup

1. Download the dataset and organize it in the following structure:


├── yolonas_l
│ ├── data
│ ├── custom_data.yaml
│ └── ...
│ ├── ...
│ └── ...

markdown


Place your dataset annotations and images in the `data` directory, and create a `.yaml` file with dataset configuration.

2. Create or modify a YAML file for your custom YOLONAS_l model configuration.

## Usage

1. Open and run the `.ipynb` notebook to train the Car Scratchs and Dents Detection model.

2. Follow the instructions in the notebook for training parameters, dataset paths, and customization.

3. Trained model weights will be saved in the `checkpoints` directory.

## References

- [YOLONAS GitHub Repository](https://github.com/Deci-AI/super-gradients/blob/master/YOLONAS)



