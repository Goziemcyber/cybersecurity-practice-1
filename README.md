# Cybersecurity Practice — System & Network Enumeration

This is my first cybersecurity practical exercise.
I am learning step by step how to understand my system and network using basic commands.

## 🔹 Linux Commands I Practiced
ls        # list files
pwd       # show current location
cd        # move into a folder
cd ..     # move back one folder

## 🔹 Network Commands I Practiced

### ifconfig (Safe Version)
eth0:
    inet 10.0.2.XX
    netmask 255.255.255.0
    ether 08:00:27:XX:XX:XX

lo:
    inet 127.0.0.1

### netstat -ano (Safe Version)
Proto  Local Address        Foreign Address        State         PID
TCP    192.168.0.XX:443      52.113.XXX.XXX:443     ESTABLISHED   XXX
TCP    0.0.0.0:135           0.0.0.0:0              LISTENING     XXX

## 🔹 What I Learned
- How to move around in Linux
- How to list files and folders
- How to see my IP address safely
- How to check open ports
- How to view active network connections

## 🔹 More to Come
I will continue learning:
- Network traffic analysis
- Log analysis
- SIEM
- Python for cybersecurity
- Vulnerability analysis
