# Code Repository


|                |   DOI  |
|----------------|----------|
| Paper          | Coming soon ! |
| Training Dataset | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7692392.svg)](https://doi.org/10.5281/zenodo.7692392) |
| NuCount Model  | [![DOI](https://img.shields.io/badge/huggingface-model-yellow)](https://doi.org/10.57967/hf/0418) |

## 1 - Setup Environment

Please clone this repository localy:

```bash
git clone https://github.com/andysaurin/3DL_NuCount
```

Then create a Python virtual environment (Anaconda, Venv ...) and install all the packages and dependencies required by 3DL_NuCount:

```bash
pip install -r requirements.txt
```

## 2 - Dataset, model and inference demo volume

The dataset used to train our own fine-tuned version of StarDist3D model is available from Zenodo for download. Please check the __dataset/readme.txt__

The model is available from HuggingFace for download. Please check the __model/3dl_nucount/readme.txt__

The demo inference volume is available for download. Please check the __images/readme.txt__

## 3 - Training & Fine Tuning a Stardist3D pretrained model

Please use __3dl_nucount_training.ipynb__ Notebook and follow the instructions inside to train your own model.

## 4 - Counting

Please use __3dl_nucount_inference.ipynb__ Notebook and follow the instructions to count the cell from the demo volume provided.

## 5 - License
This code repository is release under the [GPL v3.0 License](https://github.com/andysaurin/3DL_NuCount/blob/master/LICENSE)

