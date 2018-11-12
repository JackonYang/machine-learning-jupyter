# Machine Learning Jupyter Notebooks

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
