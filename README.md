This is nothing but twitching of Pythons SimpleHttpServer which could be used
to share files but not folders.

the modification includes, first zipping the folder and then delivering it as
a zip file, ready to download.

#USE CASES:
To share file across Local Network or outside.

#How to Start server:

download the yo.py file in this repo, lets assume you put the file at path:
"/x"
Now lets assume you want to share a folder at path:
"/y"

##Procedure:
cd "/y"
python -m /x 8000
<--- 8000 is a port address, you can use any other port address like 8080 --->

Lets assume you used port address 8000

now to access server on the computer that started server, go to browser and:

http://localhost:8000

to access in Local Network:

find IP address of computer on which server is running,
lets assume it is 192.168.4.110

open browser and do:

192.168.4.110:8000

8000 is the port which we choose while starting the server, if you choose
other port address, use that.

THANK YOU
