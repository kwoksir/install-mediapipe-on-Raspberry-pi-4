# Install OpenCV & Mediapipe on Raspberry Pi4B

### Run on Raspberry Pi4B 8GB and based on Debian Bullseye (64-bit)
![cap](https://github.com/kwoksir/install-mediapipe-on-Raspberry-pi-4/assets/61585411/3891a342-865f-4fa5-9dfd-1ae82bd10c87)

### Python version == 3.9.2

[Install OpenCV & Mediapipe on Raspberry Pi 4B](https://www.youtube.com/watch?v=j11CKdGFOWg) -YouTube demo


## Update and upgrade the Raspberry Pi OS
```sudo apt-get update```

```sudo apt-get upgrade```

## Install OpenCV related packages

HDF5 is a file format and library for storing scientific data. HDF5 was designed and implemented to address the deficiencies of HDF4.x. It has a more powerful and flexible data model, supports files larger than 2 GB, and supports parallel I/O.

```sudo apt-get install -y libhdf5-dev```

ATLAS is an approach for the automatic generation and optimization of numerical software. Currently ATLAS supplies optimized versions for the complete set of linear algebra kernels known as the Basic Linear Algebra Subroutines (BLAS), and a subset of the linear algebra routines in the LAPACK library.

```sudo apt-get install -y libatlas-base-dev```

Install QT GUI related packages
```sudo apt-get install -y python3-pyqt5```

## Install Python related packages

### Update pip package

```python3 -m pip install --upgrade pip```

### Install Matplotlib package

```python3 -m pip install matplotlib```

### Install imutils package

```python3 -m pip install imutils```

## Install Mediapipe package (OpenCV will be installed automatically (opencv-contrib-python==4.8.0.76)

Install Mediapipe 

```python3 -m pip install mediapipe```
