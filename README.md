# Face Recognition Setup Instructions

## Introduction

This facial recognition system is designed for CPU utilization on light single-board computers like Raspberry Pi 3 or Orange Pi 3. Ensure that all the required dependencies are installed. Below are the commands for Raspberry Pi or Linux-based computers and Conda environments.

### For Raspberry Pi or Linux-based Computers:

```bash
### For Raspberry Pi or Linux-based Computers:

sudo apt install cmake build-essential pkg-config git
sudo apt install libjpeg-dev libtiff-dev libjasper-dev libpng-dev libwebp-dev libopenexr-dev
sudo apt install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev libdc1394-22-dev libgstreamer-plugins-base1.0-dev libgstreamer1.0-dev
sudo apt install libgtk-3-dev libqtgui4 libqtwebkit4 libqt4-test python3-pyqt5
sudo apt install libatlas-base-dev liblapacke-dev gfortran
sudo apt install libhdf5-dev libhdf5-103
sudo apt install python3-dev python3-pip python3-numpy

### Or use the code below if youre using conda enviroment

conda install -c conda-forge cmake pkg-config git
conda install -c conda-forge libjpeg-turbo libtiff libjasper libpng libwebp libopenexr
conda install -c conda-forge libavcodec libavformat libswscale libv4l libxvidcore libx264 libdc1394 libgstreamer-plugins-base libgstreamer
conda install -c conda-forge gtk qt pyqt
conda install -c conda-forge libatlas liblapacke
conda install -c conda-forge hdf5
conda install -c conda-forge python=3.8 pip numpy
