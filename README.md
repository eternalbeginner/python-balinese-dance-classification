# Balinese Dance Classification

An AI project that use machine learning to classify traditional Balinese dance. The classification method will use _Convolutional Neural Network_ (CNN).

## Installation

First-thing-first is to clone the repository by following the command below

```sh
git clone https://github.com/eternalbeginner/python-balinese-dance-classification.git
cd python-balinese-dance-classification # to go inside the newly cloned directory
```

Then, the next step after cloning the repository is to install the neccesary dependencies. You can do that by following the command below

```sh
# auto installing from the requirements.txt file
pip install --no-cache-dir -r requirements.txt

# individually install dependencies
pip install ipython
pip install matplotlib
pip install numpy
pip install pandas
pip install scikit-learn
pip install seaborn
pip install tensorflow
```

> You can make sure to create `venv` first to install the dependencies locally and not globally. Virtual environment can be created using this command: `python3 -m venv ./venv` or `python -m venv ./venv`. Do the activation using the command: linux/macos `source venv/bin/activate` or windows `.\venv\Scripts\activate`. If not, please make sure that you know what you're doing.

#### CUDA (Optional)

You can do the CUDA installation if neccesary/needed. You can download the CUDA Toolkit [here][url-cuda-toolkit-download] and cuDNN [here][url-cudnn-download]. Please refer to [this video][url-yt-cuda-cudnn-installation] for installation tutorial.

## Usage

For the usage, you can install some extension in your VS Code for Python and Jupyter Notebook. Then, run it from there!

- Google Colab compatibility: _Coming Soon_
- Paperspace Gradient compatibility: _Coming Soon_

[url-cuda-toolkit-download]: https://developer.nvidia.com/cuda-downloads
[url-cudnn-download]: https://developer.nvidia.com/cudnn
[url-yt-cuda-cudnn-installation]: https://www.youtube.com/watch?v=OEFKlRSd8Ic
