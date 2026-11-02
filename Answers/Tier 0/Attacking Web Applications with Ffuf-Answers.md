### In addition to the directory we found above, there is another directory that can be found. What is it?
```
forum
```

### Try to use what you learned in this section to fuzz the '/blog' directory and find all pages. One of them should contain a flag. What is the flag?
```
HTB{bru73_f0r_c0mm0n_p455w0rd5}
```

### Try to repeat what you learned so far to find more files/directories. One of them should give you a flag. What is the content of the flag?
```
HTB{fuzz1n6_7h3_w3b!}
```

### Try running a sub-domain fuzzing test on 'inlanefreight.com' to find a customer sub-domain portal. What is the full domain of it?
```
customer.inlanefreight.com
```

### Try running a VHost fuzzing scan on 'academy.htb', and see what other VHosts you get. What other VHosts did you get?
```
test.academy.htb
```

### Using what you learned in this section, run a parameter fuzzing scan on this page. What is the parameter accepted by this webpage?
```
user
```

### Try to create the 'ids.txt' wordlist, identify the accepted value with a fuzzing scan, and then use it in a 'POST' request with 'curl' to collect the flag. What is the content of the flag?
```
HTB{p4r4m373r_fuzz1n6_15_k3y!}
```

### Run a sub-domain/vhost fuzzing scan on '*.academy.htb' for the IP shown above. What are all the sub-domains you can identify? (Only write the sub-domain name)
```
archive test faculty
```

### Before you run your page fuzzing scan, you should first run an extension fuzzing scan. What are the different extensions accepted by the domains?
```
php7 phps php
```

### One of the pages you will identify should say 'You don't have access!'. What is the full page URL?
```
http://faculty.academy.htb:PORT/courses/linux-security.php7
```

### In the page from the previous question, you should be able to find multiple parameters that are accepted by the page. What are they?
```
username user
```

### Try fuzzing the parameters you identified for working values. One of them should return a flag. What is the content of the flag?
```
HTB{w3b_fuzz1n6_m4573r}
```
