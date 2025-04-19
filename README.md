# Deep Learning Final Project: Game of Life

This project aims to use Deep Learning models to learn the rules of [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

## Environment setup:

(This is the environment I personally use for the training, you can use other similar local setup or use the Kaggle online notebook)

- OS: Windows 11
- GPU: NVIDIA GeForce RTX 3060 Laptop GPU
- CUDA 11.2.2
- cuDNN 8.1.1

## Python related:

Install pyenv to make it easier to switch Python versions:

```sh
choco install pyenv-win
pyenv install 3.10.5

pyenv rehash
pyenv global 3.10.5
```

Create a venv under the project directory, and activate it:

```sh
python -m venv tf
.\tf\Scripts\activate
```

Install packages:

```sh
pip install -r requirements.txt

# Or install the packages manually, and add any packages missing:
pip install "numpy<2"
pip install tensorflow==2.10.0
pip install matplotlib
pip install seaborn
pip install scipy
# and more..
```

To freeze all package requirements:

```sh
pip freeze > requirements.txt
```
