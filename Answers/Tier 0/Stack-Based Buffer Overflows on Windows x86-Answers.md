### Try to RDP into the Windows VM using one of the methods mentioned above, and apply what you learned in this module. When you try to attach to 'Free CD to MP3 Converter', what is the name of its process?
```
cdextract
```

### Try to fuzz the program with '.wav' files of increments of 1000 bytes '1000, 2000, 3000...', and find the smallest payload size that crashes the program and overwrites EIP with '41414141'.
```
5000
```

### If you find the value 'B5eB' in EIP after sending your pattern, what would be the EIP offset?
```
915
```

### Try to repeat what you learned in this section to identify all bad characters for our program. What is the total number of bad characters you identified? "Note: the result may differ from what was shown in this section"
```
0
```

### Try to search the 'cdextract.exe' binary for the 'PUSH ESP; RET' instruction as pattern '54C3'. What is the address of the first result you get?
```
00457418
```

### In the 'Documents' folder you will find a shortcut that runs the 'Free CD to MP3' program as admin. Try to use the exploit on it to get a command prompt as the admin user, and read the flag in the admin's Desktop.
```
HTB{l0c4l_0v3rfl0w_m4573r}
```

### Try the gradual remote fuzzing exercise shown above. What is the payload size that crashes the program 'in bytes'?
```
1500
```

### The above server has 'CloudMe' listening on port 8889. Try to use the exploit you built to get a reverse shell and read the flag on the user's Desktop.
```
HTB{r3m073_buff3r_0v3rfl0w3r}
```

### What is the flag found on the Administrator's Desktop folder you got after gaining remote code execution?
```
HTB{r3m073_3xpl0174710n_n1nj4}
```
