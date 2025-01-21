#This is a Python executable Network Scanner terminal tool.

This code works to scan an IP address or an IP range and identify its MAC address.
The code works by creating an ARP (Address Resolution Protocol) request, then broadcasting it, then receiving a response(MAC address), then pinging the
response to confirm and finally printing the results.

MODULES USED:
— The module SCAPY was used to create the ARP request.
— The module ARGPARSE was used to add command-line interface options. (This was earlier implemented using OPTPARSE, but later I decided to update it to ARGPARSE to make it more Python3 compatible)

This code is well functioning and tested and gives useful error information.

I got the idea for this code from the course 'Learn Python & Ethical Hacking From Scratch' by Zaid Sabih, zSecurity.
