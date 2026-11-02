### Perform an Nmap scan of the target. What does Nmap display as the version of the service running on port 8080?
```
Apache Tomcat
```

### Perform an Nmap scan of the target and identify the non-default port that the telnet service is running on.
```
2323
```

### List the SMB shares available on the target host. Connect to the available share as the bob user. Once connected, access the folder called 'flag' and submit the contents of the flag.txt file.
```
dceece590f3284c3866305eb2473d099
```

### Try running some of the web enumeration techniques you learned in this section on the server above, and use the info you get to get the flag.
```
HTB{w3b_3num3r4710n_r3v34l5_53cr375}
```

### Try to identify the services running on the server above, and then try to search to find public exploits to exploit them. Once you do, try to get the content of the '/flag.txt' file. (note: the web server may take a few seconds to start)
```
HTB{my_f1r57_h4ck}
```

### SSH into the server above with the provided credentials, and use the '-p xxxxxx' to specify the port shown above. Once you login, try to find a way to move to 'user2', to get the flag in '/home/user2/flag.txt'.
```
HTB{l473r4l_m0v3m3n7_70_4n07h3r_u53r}
```

### Once you gain access to 'user2', try to find a way to escalate your privileges to root, to get the flag in '/root/flag.txt'.
```
HTB{pr1v1l363_35c4l4710n_2_r007}
```

### Run an nmap script scan on the target. What is the Apache version running on the server? (answer format: X.X.XX)
```
2.4.18
```

### Spawn the target VM and type "DONE" in the answer field to continue enumeration.
```
DONE
```

### Gain a foothold on the target and submit the user.txt flag
```
79c03865431abf47b90ef24b9695e148
```

### Escalate privileges and submit the root.txt flag.
```
de5e5d6619862a8aa5b9b212314e0cdd
```

### Spawn the target, gain a foothold and submit the contents of the user.txt flag.
```
7002d65b149b0a4d19132a66feed21d8
```

### After obtaining a foothold on the target, escalate privileges to root and submit the contents of the root.txt flag.
```
f1fba6e9f71efb2630e6e34da6387842
```
