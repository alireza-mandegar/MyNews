# CVE-2023-22937
Splunk Vulnerability that is about lookup that can upload any file with no argument on extention.

# svchost.exe
SvcHost stands for **S**er**v**i**c**e **Host**, is a system process that can host one or more windows service in the windows NT Family of OS.

# LOLBAS
LOLBAS is stand for **L**iving **O**ff the **L**and **B**inaries **A**nd **S**cripts; and its stand for a method of attack.

# mstsc.exe
MsTSC stands for **M**icrosoft **T**erminal **S**ervices **C**lient.
RDP(Remote Desktop Connection)

# tscon.exe
Session Connection Utility.
The ts stand for **T**erminal **S**erver
Now being called Remote Desktop Service

# CVE-2022-1388
Is a missing authentication for critical function vulnerability (CWE-306). Any attacker able to send HTTPREQUESTS to a BIG-IP system through the management port and/or a self IP Address can execute arbitrary system command as root.

# event code 5858
Is a common issue occurring while using the windows server with applications that use IWebSService:Execquery

# CVE-2023-040477
Allow attackers to execute arbitrary code on the victim target system with only opening a compromised archive file.
"The issue results from the lack of proper validation of user-supplied data, which can result in memory access past the end of an allocated buffer."
"The specific flaw exists with in the processing of recovery volumes"

# wazuh
## XDR
E**x**tended **D**etection and **Response** is a new approach to threat detection and response that provides holistic protection against cbyerattacks, unauthorized access and misuse.

*Wazuh* is used to **collect**, **aggregate**, **index** and **analyse** security data, helping arganizations detect **intusions**, **threats** and **behavioral anomalies**.

# Sysmon Event IDs
1--> Process Creation
2--> A process Changed a File Creation Time
3--> Network Connection
4--> Sysmon Service State Changed
5--> Process Terminated
6--> Driver Loaded
7--> Image Loaded
8--> Create Remote Thread
9--> Raw Access Read
10--> Process Access
11--> File Creation
12--> Registry Event (Object Create and Delete)
13--> Registry Event (Value Set)
14--> Registry Event (Key and Value Rename)
15--> File Create Stream Hash
16--> Sysmon Config State Change
17--> Pipe Created
18--> Pipe Connected
19--> WmiEventFilter Activity Detected
20--> WmiEventconsumer Activity Detected
21--> WmiEventconsumerToFilter Activity Detected
22--> DNS Event
23--> File Delete
24--> Clipboard Change
225--> Error

# mmc.exe
Stand for **M**icrosoft **M**anagement **C**onsole; One of the most important computer management, contains several others including event viewer, disk management and device manager.

# \ntsvcs
Sysmon Event ID = 17, 18
Its about pipe create and connect. this pipe is about rpc protocol. all about this pipe is [here](https://en.m.wikipedia.org/wiki/Service_Control_Manager)

# RPC Protocol
Stand for **R**emote **P**rocedure **C**all; Remote Procedure Call (RPC) is a powerful technique for constructing distributed, client-server based applications. It is based on extending the conventional local procedure calling so that the called procedure need not exist in the same address space as the calling procedure. The two processes may be on the same system, or they may be on different systems with a network connecting them. 

![When making a Remote Procedure Call](https://media.geeksforgeeks.org/wp-content/uploads/operating-system-remote-procedure-call-1.png)
[More about this Protocol](https://www.geeksforgeeks.org/remote-procedure-call-rpc-in-operating-system/)


