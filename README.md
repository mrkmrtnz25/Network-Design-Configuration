# Useful powershell commands

### Commands to install ADDS and ADDS forrest with DNS
```
install-windowsfeature ad-domain-services  -IncludeAllSubFeature -IncludeManagementTools4
```
```
Install-ADDSForest  -DomainName  "mark.ca" -installDns
```
![Alt text](C:\Users\mrkmr\Documents\GitHub\Network-Design-Configuration\topology.png)
