# Car Damage Detection with Detectron2

This repository contains code for training a Car Damage Detection model using Detectron2. The model identifies scratches and dents, drawing bounding boxes around them.

## Dataset

The dataset for this project can be downloaded [here](provide_link_to_dataset). Organize the dataset in the following structure:

├── car_damage_detection │
│ ├── data │
│ │ ├── images │
│ │ ├── annotations │
│ │ └── ... │
│ ├── custom_data.yaml │
│ └── ...



Place your dataset annotations (in COCO format) and images in the `data` directory.

## Environment Setup

1. Create a new Python/Anaconda environment.

2. Install the necessary packages:

    ```bash
    conda install numpy pandas matplotlib opencv cython jupyter
    ```

3. Install Detectron2:

    ```bash
    pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu102/torch1.7/index.html
    ```

4. If you have a supported GPU, install GPU-related packages:

    ```bash
    conda install torch torchvision torchaudio cudatoolkit=10.2 -c pytorch
    ```

    If you don't have a supported GPU or want to train on a CPU, run:

    ```bash
    conda install torch torchvision torchaudio cpuonly -c pytorch
    ```

## Training

1. Open and run the `.ipynb` notebook to train the Car Damage Detection model.

2. Follow the instructions in the notebook for training parameters, dataset paths, and customization.

3. Trained model weights will be saved in the `checkpoints` directory.

## Inference

Use the trained model for inference using the provided scripts or by integrating it into your own applications.

## Acknowledgments

This project was inspired by [link to original project if applicable].

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.
