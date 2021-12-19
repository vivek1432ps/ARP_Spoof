#ARP spoofing is a malicious attack in which the hacker sends falsified ARP in a network. Every node in a connected network has an ARP table through which we identify the IP address and the MAC address of the connected devices.
#What aim to send an ARP broadcast to find our desired IP which needs to be spoofed, and then spoof the gateway, as well as the target by updating their ARP Tables. This would enable the network packets sent by the target, to pass from our machine to the network gateway making the ARP spoof successful
#To design a python script to create an ARP spoofer, we require the Scapy module. Scapy is a very powerful packet manipulation tool and library which is completely written in python

    # 1.Get the IP address that we want to spoof
    # 2.Get the MAC address of the IP that we want to spoof
    # 3.Then create a spoofing packet using the ARP() function to set the target IP, Spoof IP and it’s MAC address that we found above.
    # 4.Start the spoofing
    # 5.Display the information of the numbers of packets sent
    # 6.Finally, re-set the ARP tables of the spoofed address to defaults after spoofing
