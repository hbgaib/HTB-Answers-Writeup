### To get the flag, start the above exercise, then use cURL to download the file returned by '/download.php' in the server shown above.

Open your Terminal, use curl command to get the answer
```
curl [TARGET]/download.php
```

### Send a GET request to the above server, and read the response headers to find the version of Apache running on the server, then submit it as the answer. (answer format: X.Y.ZZ)

Use curl with verbose flag to get the full response header 
```
curl -v [TARGET]/download.php
```

### The server above loads the flag after the page is loaded. Use the Network tab in the browser devtools to see what requests are made by the page, and find the request to the flag.

Open the target in your browser, then open your devtools by pressing F12. Head to the Network tab and read all of the requests made by the target.
![[Pasted image 20260803183730.png]]

Curl the link that your target requests by using
```
curl http://[TARGET]/flag_xxxxx.txt
```
