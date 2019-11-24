IPv6Tunnel.ps1
==========
PowerShell script to build/rebuild a 6in4 (IPv6-in-IPv4) tunnel on Windows 10 with [Hurricane Electric Free IPv6 Tunnel Broker](https://tunnelbroker.net)


-Requires at minimum Windows PowerShell 4.0.  
-This script needs administrtive rights. 
It will check if PowerShell/PowerShell ISE is running with elevated privileges as administrator.
If not it is trying to self-elevate. 

- [X] Initial version using netsh
- [ ] Replace netsh with PowerShell cmdlets (netsh is deprecated)
