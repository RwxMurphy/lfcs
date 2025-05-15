## Remote GUI
The admin decides which client to install on the server. Typically some 
version of VNC is used on linux systems. If the admin want to allow windows 
users to log in RDP(remote desktop protocol) is often used.

## Remote Text-mode login
Almost all linux system use Open SSH(secure shell) to login to remote systems.


**How it works** The server has a SSH daemon running in the background listning 
for connectons request. The local machine has a SSH client which is used to 
send the connection request to the server.


### **Basic SSH command**

```bash
$ ssh aaron@192.168.0.17
```
