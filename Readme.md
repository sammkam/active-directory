# Active Directory setup

1 Use `Sconfig` to'
    Change hostname
    Change Ipaddress (192.168.42.155) and DNS to itself

2 Installed Windows Activedirectory feature  
```shell
Install-WindowsFeature AD-Domain-Service -IncludeManageentTools
```