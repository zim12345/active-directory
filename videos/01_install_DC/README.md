#01 Installing the Domain Controller

1. use `sconfig` to:
-change the hostname
-change the IP address to static
-change the Dns server to our own IP address

2. Install the Active Directory windows Feature

```

Install-WindowsFeature AD-Domain-Services -IncludeManagementTools

```