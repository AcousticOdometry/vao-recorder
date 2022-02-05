# Visual and Acoustic recorder

Visual and Acoustic Odometry recorder using python. Devices: RealSense D435i
camera, RODE VideoMicNTG and smartLav+ microphones

# Setup

Clone this repository to your local machine. Detailed instructions about
cloning repositories and installing python dependencies can be found [here](https://docs.google.com/document/d/15Mj3x9Im7Yfz3sPo5f4dUjQZgabjVtIL2RBHvM2798E/edit?usp=sharing).

## Install Python (3.5 - 3.9)
Do not install the latest version of Python (currently 3.10) as it is not
compatible with Intel RealSense SDK yet.

https://www.python.org/downloads/

## Install Intel RealSense SDK 2.0

https://github.com/IntelRealSense/librealsense/releases

## Install dependencies
Open a terminal in the directory where this file is located. Then create a
virtual environment:
```
python3 -m venv venv
```

Activate the environment on Windows:
```
venv\Scripts\activate.bat
```
or on MacOS and Linux:
```
source venv/bin/activate
```

Finally, install dependencies with pip:
```
pip install -r requirements.txt
```