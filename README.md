# AI stock analysis

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/AI-stock-analysis/blob/master/AI-stock-analysis.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/AI-stock-analysis/blob/master/LICENSE)

Final practical project for Artificial Intelligence studies. Project aims to use 3 different models (`LSTM`, `GRU` and `AMIGA`) to predict stock prices and choose the best one by comparing their `RMSE`.

## Usage

### Automatic launch

1. [**Recommended**] To run in browser click on [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/AI-stock-analysis/blob/master/AI-stock-analysis.ipynb) badge.
2. [Or a less convenient alternative] To launch locally on Windows just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/AI-stock-analysis/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/AI-stock-analysis.git
```

2. Navigate into project:

```bash
cd AI-stock-analysis/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook AI-stock-analysis.ipynb
```
