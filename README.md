# PhySim-11p
Simulation model for IEEE 802.11p physical layer in MATLAB

The provided code simulates the physical layer of the IEEE 802.11p standard.
It is written in Matlab. The goal is to simplify the simulation of the 
802.11p standard but maintaining control over of process. Therefore, it can
be easily modified to test techniques in the different steps of wireless transmission.
The main folder contains two subfolders:

1. All the code files needed to simulate a wireless transmission using 802.11p
are located in the folder code.

    To execute the code, you must run the Selec_grap.m file that presents three
    options:
        Simulated PHY graph
        Graph of the theoretical models
        Graphic comparison of PHY and theoretical models

    Necessary datasets are included so that Selec_grap.m runs without any
    inconvenience. 
    If you want to re-simulate the physical layer, you must first run the file 
    simulation_802_11_p.m  and then proceed to run Selec_grap.m
    
    This version includes a realistic channel model for vehicular communications

2. The folder html contains the user manual with the commented code. 
You must run the Selec_grap.html file that is the main one.

