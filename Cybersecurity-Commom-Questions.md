# System Administration
## How do you change your DNS settings in Linux/Windows?
### On windows
-  from command line, start netsh >  
```cmd
interface show interface 
interface ip set dns name="ADAPTER-NAME" source="static" address="X.X.X.X"
```
- From Powershell
```cmd
PS C:\> Set-DnsClientServerAddress -InterfaceIndex 12 -ServerAddresses ("10.0.0.1","10.0.0.2")
```

### On Linux
- open a terminal
- use nano (or vi) to edit /etc/resolv.conf
- add a line of "nameserver x.x.x.x" with x.x.x.x being the IP address of your DNS server.
- save the file and you're done

# Encryption
## Does TLS use symmetric or asymmetric encryption?
### TLS uses both asymmetric encryption and symmetric encryption
###  The TLS handshake is done using asymmetric while the bulk data requires speed and therefore symmetric encrytion is used.

## What’s the difference between symmetric and public-key cryptography?
### symmetric uses a single key while public-key uses two