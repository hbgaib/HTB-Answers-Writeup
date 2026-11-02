### Find out the machine hardware name and submit it as the answer.
```
x86_64
```

### What is the path to htb-student's home directory?
```
/home/htb-student
```

### What is the path to the htb-student's mail?
```
/var/mail/htb-student
```

### Which shell is specified for the htb-student user?
```
/bin/bash
```

### Which kernel release is installed on the system? (Format: 1.22.3)
```
4.15.0
```

### What is the name of the network interface that MTU is set to 1500?
```
ens192
```

### What is the name of the hidden "history" file in the htb-user's home directory?
```
.bash_history
```

### What is the index number of the "sudoers" file in the "/etc" directory?
```
147627
```

### What is the name of the last modified file in the "/var/backups" directory?
```
apt.extended_states.0
```

### What is the inode number of the "shadow.bak" file in the "/var/backups" directory?
```
265293
```

### What is the name of the config file that has been created after 2020-03-03 and is smaller than 28k but larger than 25k?
```
00-mesa-defaults.conf
```

### How many files exist on the system that have the ".bak" extension?
```
4
```

### Submit the full path of the "xxd" binary.
```
/usr/bin/xxd
```

### How many files exist on the system that have the ".log" file extension?
```
32
```

### How many total packages are installed on the target system?
```
737
```

### How many services are listening on the target system on all interfaces? (Not on localhost and IPv4 only)
```
7
```

### Determine what user the ProFTPd server is running under. Submit the username as the answer.
```
proftpd
```

### Use cURL from your Pwnbox (not the target machine) to obtain the source code of the "https://www.inlanefreight.com" website and filter all unique paths (https://www.inlanefreight.com/directory" or "/another/directory") of that domain. Submit the number of these paths as the answer.
```
34
```

### Which option needs to be set to create a home directory for a new user using "useradd" command?
```
-m
```

### Which option needs to be set to lock a user account using the "usermod" command? (long version of the option)
```
--lock
```

### Which option needs to be set to execute a command as a different user using the "su" command? (long version of the option)
```
--command
```

### Use the "systemctl" command to list all units of services and submit the unit name with the description "Load AppArmor profiles managed internally by snapd" as the answer.
```
snapd.apparmor.service
```

### What is the Type of the service of the "dconf.service"?
```
dbus
```

### Find a way to start a simple HTTP server inside Pwnbox or your local VM using "npm". Submit the command that starts the web server on port 8080 (use the short argument to specify the port number).
```
http-server -p 8080
```

### Find a way to start a simple HTTP server inside Pwnbox or your local VM using "php". Submit the command that starts the web server on the localhost (127.0.0.1) on port 8080.
```
php -S 127.0.0.1:8080
```

### How many partitions exist in our Pwnbox? (Format: 0)
```
3
```
