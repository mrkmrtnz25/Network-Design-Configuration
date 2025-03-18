# Useful powershell commands

### Commands to install ADDS and ADDS forrest with DNS
```
install-windowsfeature ad-domain-services  -IncludeAllSubFeature -IncludeManagementTools4
```
```
Install-ADDSForest  -DomainName  "mark.ca" -installDns
```
![alt text](https://github.com/mrkmrtnz25/Network-Design-Configuration/blob/main/topology.png?raw=true)
