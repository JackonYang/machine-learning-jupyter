# Machine Learning Jupyter Notebooks

## Table of Contents

#### Hidden Markov Model

- [the basic model of fever](hidden_markov_model/01_hmm_fever.ipynb)
- [supervised learning for Chinese words segmentation](hidden_markov_model/02_hmm_supervised_learning_segmentation.ipynb)
- [predict using viterbi -- Part-of-Speech](hidden_markov_model/03_predict_viterbi_pos.ipynb)
- [predict using viterbi -- Chinese segmentation](hidden_markov_model/04_predict_viterbi_zh_segmentation.ipynb)

references:

1. [统计学习方法 -- 李航](https://book.douban.com/subject/10590856/)
2. [Speech and Language Processing -- Daniel Jurafsky](https://book.douban.com/subject/2403834/)
3. [隐马尔科夫模型（HMM）及其Python实现](https://applenob.github.io/hmm.html)

## ENV

Python 3.7.0

```bash
$ pip3 install --upgrade pip
$ pip3 install virtualenv
$ virtualenv venv
$ source venv/bin/activate
(venv) xxx $
```

```bash
$ python --version
Python 3.7.0
$ pip --version
pip 18.0 from /Users/jackon/proj/deepfive/venv/lib/python3.7/site-packages/pip (python 3.7)
$ pip install -r requirements.txt
```

#### install Lightgbm on Mac

Only Apple Clang version 8.1 or higher is supported.

Install CMake (3.12 or higher):

```bash
brew install cmake
```

Install OpenMP:

```bash
brew install libomp
```

Run the following commands:

```bash
git clone --recursive https://github.com/Microsoft/LightGBM ; cd LightGBM
mkdir build ; cd build
cmake ..
make -j4
```

```bash
pip install --no-binary :all: lightgbm
```
