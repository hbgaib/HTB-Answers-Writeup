### Utilizing the output shown in question-1.png, who is the server in this communication? (IP Address)
```
174.143.213.184
```

### Were absolute or relative sequence numbers used during the capture? (see question-1.zip to answer)
```
relative
```

### If I wish to start a capture without hostname resolution, verbose output, showing contents in ASCII and hex, and grab the first 100 packets; what are the switches used? please answer in the order the switches are asked for in the question.
```
-nvXc 100
```

### Given the capture file at /tmp/capture.pcap, what tcpdump command will enable you to read from the capture and show the output contents in Hex and ASCII? (Please use best practices when using switches)
```
sudo tcpdump -Xr /tmp/capture.pcap
```

### What TCPDump switch will increase the verbosity of our output? ( Include the - with the proper switch )
```
-v
```

### What built in terminal help reference can tell us more about TCPDump?
```
man
```

### What TCPDump switch will let me write my output to a file?
```
-w
```

### What TCPDump switch will allow us to pipe the contents of a pcap file out to another function such as 'grep'?
```
-l
```

### True or False: The filter "port" looks at source and destination traffic.
```
True
```

### If we wished to filter out ICMP traffic from our capture, what filter could we use? ( word only, not symbol please.)
```
not icmp
```

### What command will show you where / if TCPDump is installed?
```
which tcpdump
```

### How do you start a capture with TCPDump to capture on eth0?
```
tcpdump -i eth0
```

### What switch will provide more verbosity in your output?
```
-v
```

### What switch will write your capture output to a .pcap file?
```
-w
```

### What switch will read a capture from a .pcap file?
```
-r
```

### What switch will show the contents of a capture in Hex and ASCII?
```
-X
```

### What filter will allow me to see traffic coming from or destined to the host with an ip of 10.10.20.1?
```
host 10.10.20.1
```

### What filter will allow me to capture based on either of two options?
```
or
```

### True or False: TCPDump will resolve IPs to hostnames by default.
```
TRue
```

### What are the client and server port numbers used in first full TCP three-way handshake? (low number first then high number)
```
80 43806
```

### Based on the traffic seen in the pcap file, who is the DNS server in this network segment? (ip address)
```
172.16.146.1
```

### True or False: Wireshark can run on both Windows and Linux.
```
True
```

### Which Pane allows a user to see a summary of each packet grabbed during the capture?
```
Packet List
```

### Which pane provides you insight into the traffic you captured and displays it in both ASCII and Hex?
```
Packet Bytes
```

### What switch is used with TShark to list possible interfaces to capture on?
```
-D
```

### What switch allows us to apply filters in TShark?
```
-f
```

### Is a capture filter applied before the capture starts or after? (answer before or after)
```
before
```

### Which plugin tab can provide us with a way to view conversation metadata and even protocol breakdowns for the entire PCAP file?
```
Statistics
```

### What plugin tab will allow me to accomplish tasks such as applying filters, following streams, and viewing expert info?
```
Analyze
```

### What stream oriented Transport protocol enables us to follow and rebuild conversations and the included data?
```
tcp
```

### True or False: Wireshark can extract files from HTTP traffic.
```
True
```

### True or False: The ftp-data filter will show us any data sent over TCP port 21.
```
False
```

### What was the filename of the image that contained a certain Transformer Leader? (name.filetype)
```
Rise-Up.jpg
```

### Which employee is suspected of performing potentially malicious actions in the live environment?
```
bob
```

### What was the name of the new user created on mrb3n's host?
```
hacker
```

### How many total packets were there in the Guided-analysis PCAP?
```
44
```

### What was the suspicious port that was being used?
```
4444
```

### What user account was used to initiate the RDP connection?
```
bucky
```
