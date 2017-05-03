# This program gives the information about installing the librraries of the ADS1115 
# There is a sample code for configuring the ADC in the python code 
commads:

#sudo apt-get update
#sudo apt-get install build-essential python-dev python-smbus git
#cd ~
#git clone https://github.com/adafruit/Adafruit_Python_ADS1x15.git
#cd Adafruit_Python_ADS1x15
#sudo python setup.py install

If you see an error go back and carefully check all the previous commands were run, and that they didn't fail with an error.
To install from the Python package index connect to a terminal on the Raspberry Pi and execute the following commands:

sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus python-pip
sudo pip install adafruit-ads1x15

