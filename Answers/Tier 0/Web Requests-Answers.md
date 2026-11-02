### To get the flag, start the above exercise, then use cURL to download the file returned by '/download.php' in the server shown above.
```
HTB{64$!c_cURL_u$3r}
```

### What is the HTTP method used while intercepting the request? (case-sensitive)
```
GET
```

### Send a GET request to the above server, and read the response headers to find the version of Apache running on the server, then submit it as the answer. (answer format: X.Y.ZZ)
```
2.4.41
```

### The server above loads the flag after the page is loaded. Use the Network tab in the browser devtools to see what requests are made by the page, and find the request to the flag.
```
HTB{p493_r3qu3$t$_m0n!t0r}
```

### The exercise above seems to be broken, as it returns incorrect results. Use the browser devtools to see what is the request it is sending when we search, and use cURL to search for 'flag' and obtain the flag.
```
HTB{curl_g3773r}
```

### Obtain a session cookie through a valid login, and then use the cookie with cURL to search for the flag through a JSON POST request to '/search.php'
```
HTB{p0$t_r3p34t3r}
```

### First, try to update any city's name to be 'flag'. Then, delete any city. Once done, search for a city named 'flag' to get the flag.
```
HTB{crud_4p!_m4n!pul4t0r}
```
