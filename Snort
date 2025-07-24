                                                              #Snort
*"Learn how to use Snort to detect real-time threats, analyse recorded traffic files and indentify anomalies"*
------------
#Introduction:
  - Open-source NIDS/NIPS
  - Rule-based 
  - Contributers:
    - Martin Roesch
    - Open-source contributors
    - Cisco Talos
-------------
#Interactive Material and VM

This task opens with immediately with an Ubuntu-based Linux virtual machine. An otherwise barren desktop contains a folder - "Task-Exercises"
in which contains sample configuration and exercises folders - much of attention being directed at the ladder. 

Inside also presents a script that we'll be using to generate and direct traffic to our snort interface, and as the room directs us to do,
I run the script as sudo:

From here we're seemingly able to generate traffic as-necessary with our given tasks, represented through another instance of terminal that
prints traffic, in this case ICMP logs 

From there, we're asked to run "./.easy.sh" in the [Task-Exercises] directory - the output allows us to move onto the next task
-------------
#Introduction to IDS/IPS

IDS (Intrusion Detection System): Passive detection/monitoring solution that generates alerts based off signatures, anamolies; behaviors.
  - NIDS (Network Intrusion Detection System): Monitors the flow of traffic within a given subnet
  - HIDS (Host Intrusion Detection System): Monitors the flow of traffic from that of a single endpoint 

IPS (Intrusion Detection System): Actively intercepts traffic and observes based on given signatures, anamolies and behaviors.
Unlike IDS however, it has the ability to do more than generate alerts, rather having the ability to drop packets and terminating 
events/connections.
  - NIPS (Network Intrusion Prevention System): Actively monitors the flow of traffic within a given subnet
  - NBA (Network Behavior Analysis): Actively monitors the flow of traffic through various points of the subnet and checks for anamolies
    - Behaves similarly to NIPS but requires additional time for "baselining" to more effectively determine anamolies or outliars
  - WIPS (Wireless Intrusion Prevention System): Actively monitors the flow of wireless traffic
  - HIPS (Host-Based Intrusion Prevention System): Actively monitors the flow of traffic from that of a single endpoint

| Technique | Approach | 
| Signature-Based | Based on pre-existing/document threats and malicious behaviors; compatible through SCAP |
| Behavior-Based | Based on a given baseline and whatever outliars that may represent potentially malicious behavior(s) |
| Policy-Based | Based on the comparison of detected events to that of implement configurations and policies; focuses on policy breaches |

Snort Use Models:
  - Sniffer Mode: Reads IP packets 
  - Packet Logger Mode: Logs inbound and outbound IP traffic within network
  - NIDS: Active network monitoring capabilities and logging as determined through user-defined configurations
*SNORT has cross-platform support

-Debrief-
Wow - that was a lot of information! Much of it I was familiar with, though a refresh like this is necessary. After the presentation of
this information, a plethora of questions that query my IDS/IPS knowledge is given before I move onto the next task.
-------------
#First Interaction with Snort

Showcasing Instance Version:
  - [snort -V] (version)

Validating Configuration File:
  - [snort -c /etc/snort/snort.conf -T]
    - [-c]: Identifies configuration file path
    - [-T]: Tests configurations

Quiet Mode - Prevents Showcase of Default Banner and Initial Information about Setup on Startup
  - [snort -q]

Snort Configuration Files: Snort management file that's consisting of the given rules, plugins, actions, outputs, and methods of detection.
Only one can be used at a time.


From there, we make of the new parameters/flags we learned to answer the given questions before moving forward with the room
  - Snort instance?
    -[snort -V]

  - Check how many rules are loaded with current built in /etc/snort/snort.conf
    - [snort -c /etc/snort/snort.conf -T]

  - [Check how many rules are loaded with current build in /etc/snort/snortv2.conf]
    -[snort -c /etc/snort/snortv2.conf -T]


  














