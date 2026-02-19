# Active Directory setup

1 Use `Sconfig` to'
    Change hostname
    Change Ipaddress (192.168.42.155) and DNS to itself

2 Installed Windows Activedirectory feature  
```shell
Install-WindowsFeature AD-Domain-Service -IncludeManageentTools
```

3 Import module and make domain
```shell
C:\Users\Administrator>
PS C:\Users\Administrator> Import-Module ADDSDeployment
PS C:\Users\Administrator> Install-ADDSForest

cmdlet Install-ADDSForest at command pipeline position 1
Supply values for the following parameters:
DomainName: xyz.com
SafeModeAdministratorPassword: ************
Confirm SafeModeAdministratorPassword: ************

The target server will be configured as a domain controller and restarted when this operation is complete.
```
