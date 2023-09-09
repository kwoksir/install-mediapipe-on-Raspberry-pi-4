# Install OpenCV & Mediapipe on Raspberry Pi4B

### Run on Raspberry Pi4B 8GB and based on Debian Bullseye (64-bit)
![cap](https://github.com/kwoksir/install-mediapipe-on-Raspberry-pi-4/assets/61585411/3891a342-865f-4fa5-9dfd-1ae82bd10c87)

### Python version == 3.9.2

## Update and upgrade the Raspberry Pi OS
```sudo apt-get update```

```sudo apt-get upgrade```

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
