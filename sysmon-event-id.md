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

# \ntsvcs
Sysmon Event ID = 17, 18
Its about pipe create and connect. this pipe is about rpc protocol. all about this pipe is [here](https://en.m.wikipedia.org/wiki/Service_Control_Manager)
