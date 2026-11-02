### Using the file inclusion find the name of a user on the system that starts with "b".
```
barry
```

### Submit the contents of the flag.txt file located in the /usr/share/flags directory.
```
HTB{n3v3r_tru$t_u$3r_!nput}
```

### The above web application employs more than one filter to avoid LFI exploitation. Try to bypass these filters to read /flag.txt
```
HTB{64$!c_f!lt3r$_w0nt_$t0p_lf!}
```

### Fuzz the web application for other php scripts, and then read one of the configuration files and submit the database password as the answer
```
HTB{n3v3r_$t0r3_pl4!nt3xt_cr3d$}
```

### Try to gain RCE using one of the PHP wrappers and read the flag at /
```
HTB{d!$46l3_r3m0t3_url_!nclud3}
```

### Attack the target, gain command execution by exploiting the RFI vulnerability, and then look for the flag under one of the directories in /
```
99a8fc05f033f2fc0cf9a6f9826f83f4
```

### Use any of the techniques covered in this section to gain RCE and read the flag at /
```
HTB{upl04d+lf!+3x3cut3=rc3}
```

### Use any of the techniques covered in this section to gain RCE, then submit the output of the following command: pwd
```
/var/www/html
```

### Try to use a different technique to gain RCE and read the flag at /
```
HTB{1095_5#0u1d_n3v3r_63_3xp053d}
```

### Fuzz the web application for exposed parameters, then try to exploit it with one of the LFI wordlists to read /flag.txt
```
HTB{4u70m47!0n_f!nd5_#!dd3n_93m5}
```

### What is the full path to the php.ini file for Apache?
```
/etc/php/7.4/apache2/php.ini
```

### Edit the php.ini file to block system(), then try to execute PHP Code that uses system.  Read the /var/log/apache2/error.log file and fill in the blank: system() has been disabled for ________ reasons.
```
security
```

### Assess the web application and use a variety of techniques to gain remote code execution and find a flag in the / root directory of the file system. Submit the contents of the flag as your answer.
```
eedbb78d4800aa45573840ed6bd2d1e3
```
