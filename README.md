# Thesis_project
Securing a Smart home with a firewall

I developed my bachelor thesis on the firewall.
I gave a special focus on how a Smart home can be secured against possible cybersecurity threats by using a firewall.

For the case study I used:
1)	A raspberry Pi
2)	Smart camera
3)	Smart temperature and humidity sensor

First of all, I created a separate network called SmartHome to connect all the IoT devices and separate them from my personal devices.

Secondly, I implemented a stateful inspection firewall by using the NETFILTER of Linux Kernel.
I blocked, using the firewall, all the direct communication between the Smarthome network and the main home network.
Then, after having analyzed the traffic between the IoT devices and Internet I configured a set of rules in the firewall.
