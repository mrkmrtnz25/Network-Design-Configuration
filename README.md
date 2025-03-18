# Useful powershell commands

### Commands to install ADDS and ADDS forrest with DNS
```
install-windowsfeature ad-domain-services  -IncludeAllSubFeature -IncludeManagementTools4
```
```
Install-ADDSForest  -DomainName  "mark.ca" -installDns
```
![Image](https://github.com/user-attachments/assets/ac1d3aeb-ff0f-4012-9fab-171d0f187d0c)
