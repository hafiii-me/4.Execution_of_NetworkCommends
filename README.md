# 4.Execution_of_NetworkCommands
# NAME : MOHAMED HAFEEZ S
# REG NO : 212224040193
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>
import socket
 s=socket.socket()
 s.connect(('localhost',8000))
 while True:
 ip=input("Enter the website you want to ping ")
 s.send(ip.encode())
 print(s.recv(1024).decode()) 
 #TRACEROUTE command:
 traceroute www.google.com
## Output
![Screenshot 2025-04-29 231839](https://github.com/user-attachments/assets/1459fb28-840e-465a-a5d8-37cbc6ca63e1)

## Result
Thus Execution of Network commands Performed 
