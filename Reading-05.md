## Why this topic relates to the module
It seems that ports 445 and 139, used for Server Message Block protocol in Windows, are very commonly used in networks for file-sharing, printer-sharing, etc. Knowing these ports, what they are used for, and their vulnerabilities is foundational knowledge for anyone going into an IT field, especially with the prevelance of Windows OS in professional settings.
***
## Summary
Server Message Block has always been a network file sharing protocol. SMB uses either port 139 or 445. SMB had historically run on port 139 with NetBIOS for computers to talk to each other on the same network. Later versions (after Windows 2000) began to use 445 on top of a TCP stack. TCP allows SMB to operate over the internet. Firewalls, VPNs, VLANs, and/or MAC address filtering should be used to keep these ports secure from attack. 
***
Additional resources:<br>https://www.varonis.com/blog/smb-port
***
## Things I want to know more about
What is TCP<br>
How do firewalls, VPNs, etc. work to protect open ports