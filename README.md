# EECS149Group3
EECS 149/249A Introduction to Embedded Systems

sudo apt-get update
sudo apt-get install libhdf5-dev -y 
sudo apt-get install libhdf5-serial-dev –y 
sudo apt-get install libatlas-base-dev –y 
sudo apt-get install libjasper-dev -y 
sudo apt-get install libqtgui4 –y
sudo apt-get install libqt4-test –y
pip3 install opencv-contrib-python==4.1.0.25
pip3 install imutils
sudo pip3 install https://github.com/lhelontra/tensorflow-on-arm/releases/download/v2.2.0/tensorflow-2.2.0-cp37-none-linux_armv7l.whl #for tensorflow
pip3 install sklearn #python library for machine learning
pip3 install keras_squeezenet #squeezenet neural network model for computer vision, more feasible to deploy on hardware with limited memory

step 1.1: get images using 'python3 image.py 100'
step 1.2: press 'v' to select for user hand gesture before pressing 'a' to start, press 'n' to select background with no hand gesture isnide before pressing 'a'

step 2: train model using 'python3 training.py'

step 3: test it out using 'python3 game.py'

