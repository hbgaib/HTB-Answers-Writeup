### Connect to the database using the MySQL client from the command line. Use the 'show databases;' command to list databases in the DBMS. What is the name of the first database?
```
employees
```

### What is the department number for the 'Development' department?
```
d005
```

### What is the last name of the employee whose first name starts with "Bar" AND who was hired on 1990-01-01?
```
Mitchem
```

### In the 'titles' table, what is the number of records WHERE the employee number is greater than 10000 OR their title does NOT contain 'engineer'?
```
654
```

### Try to log in as the user 'tom'. What is the flag value shown after you successfully log in?
```
202a1d1a8b195d5e9a57e434cc16000c
```

### Login as the user with the id 5 to get the flag.
```
cdad9ecdf6f14b45ff5c4de32909caec
```

### Connect to the above MySQL server with the 'mysql' tool, and find the number of records returned when doing a 'Union' of all records in the 'employees' table and all records in the 'departments' table.
```
663
```

### Use a Union injection to get the result of 'user()'
```
root@localhost
```

### What is the password hash for 'newuser' stored in the 'users' table in the 'ilfreight' database?
```
9da2c9bcdf39d8610954e0e11ea8f45f
```

### We see in the above PHP code that '$conn' is not defined, so it must be imported using the PHP include command. Check the imported page to obtain the database password.
```
dB_passw0rd_is_flag!
```

### Find the flag by using a webshell.
```
d2b5b27ae688b6a0f1d21b7d3a0798cd
```

### What is the password hash for the user 'admin'?
```
$argon2i$v=19$m=2048,t=4,p=3$dk4wdDBraE0zZVllcEUudA$CdU8zKxmToQybvtHfs1d5nHzjxw9DhkdcVToq6HTgvU
```

### What is the root path of the web application?
```
/var/www/chattr-prod
```

### Achieve remote code execution, and submit the contents of /flag_XXXXXX.txt below.
```
061b1aeb94dec6bf5d9c27032b3c1d8d
```
