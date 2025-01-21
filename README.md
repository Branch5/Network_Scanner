#This is a Python executable terminal tool used to scan the existting network the device is connected to.

This code works to scan an IP address or an IP range and identify its MAC address.
The code works by creating an ARP (Address Resolution Protocol) request, then broadcasting it, then receiving a response(MAC address), then pinging the
response to confirm and finally printing the results.

MODULES USED:
— The module SCAPY was used to create the ARP request.
— The module ARGPARSE was used to add command-line interface options. 

(This was earlier implemented using OPTPARSE, but later I decided to update it to ARGPARSE to make it Python3 compatible)

This code is well functioning and tested and gives useful error information.

I got the idea for this code from the course 'Learn Python & Ethical Hacking From Scratch' by Zaid Sabih, zSecurity.

<br/>
<br/>

<h2>USAGE</h2>

<h4>1. Clone this Repository</h4>

<h4>2. CD to the cloned repository folder/directory</h4>

<h4>3. Run the script with the command 'python network-scanner.py'</h4>

<h4>4. Check the usage and open help with '--help' for more info</h4>

![Capture1](https://github.com/user-attachments/assets/66e352a5-db3a-4503-99a8-c62865d707cf)

<h4>5. Run 'route -n' to view the routing table and find the router gateway address</h4>

<h4>6. Run the script with the gateway address (add /24 at the end of the address) with the appropriate usage option (use sudo)</h4>

<h4>7. View the displayed network table for the gateway address and confirm all addresses</h4>

![Capture2](https://github.com/user-attachments/assets/50e4e547-dcad-45a3-8221-2d3e6401b746)
