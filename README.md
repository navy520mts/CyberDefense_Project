CyberDefense_Project
====================

This is a traffic analysis tool that can be utilized in cyber competitions which provides observers a 
graphical representation of host to host and team to team traffic and connections. 
The tool is currently being written in Python and is utilizing the Scapy library.

Scapy_test: Is just a class that allows your to play around with and see what the library scapy can do in terms of packet capture.

GUI: Has two file team and Host_GUI.

      -The team file creates the teams and displays them in a circle.
      
      -Host_GUI calls the class team and actually displays the teams on the screen and will be used to
       show the connections we are drawing from host to host.
       
      -Read comments in each file to fully understand what each does, the comments Jesse made are pretty indepth
       and helpful.
       
Connection_Class: Is our base class for creating what will be a meaningful connection.

PacketCapture: Is the class that we are using to capture all the packets and will be able tell what is a meaningful connection in a competition enviroment and store it for the GUI.
