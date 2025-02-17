# gofile-bypass
Bypass GoFile's Cold Storage System.

Easy and simple follow these few steps.

First of all check for F12 prints as they usually print the array that stores the cold storage download link in the console.

If there's an object in the console do the following to find the download:

Click on the object, Click on the data array next, then look for the "children" array, open that next, and then there'll be two options, something like 47267108-2323-2323-2323-12cfe51420a8 and [[Prototype]]: Object,

Click on the long numbers array and inside you'll see the "link" value which has the link directly to cold storage.

If you did not recieve any object in the console here's what else you can do.

The links follow the pattern of:

"https://SERVERNAME.gofile.io/download/web/LONGNUMBERARRAY/FILENAME.zip"

SERVERNAME:
You can find this easily, Click on the 3 dots on the right of the download button next to the file you want to download.

Then click properties in here you'll have general information and file information.

The server name is found under "Servers:" under File information in my case it's cold-na-phx-3
The LONGNUMBERARRAY is found under ID under General information
The filename can be found above the General information title. 

And that's how you bypass it (Note this will defo get patched as soon as gofile become aware of it as they aren't special)
( Note GoFile: No sue i just found you a bug and lyk ;) )
