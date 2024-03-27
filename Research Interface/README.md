# Research EEG Interface : 

Interface that allows anyone to test and evaluate the power of the AI model and the EEG headset in real time.


How to lauch it ? 

Material required : Muse 2

1. Install librairies : 
    => pip install tensorflow

    => pip install pygame

    => pip install numpy

    => pip install pylsl 

    => pip install threading

    => pip install csv

    => pip install sys

    

2. Lauch the stream in a new window : muselsl stream
3. Launch the visualisation in an other window to make sur the Muse 2 is well placed : muselsl view ou muselsl view --version 2
4. Lauch the python file : python interface.py