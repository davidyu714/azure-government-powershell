# Azure Government PowerShell

This repository contains a set of useful PowerShell scripts for managing an Azure Government subscription. More information on each script has been included below.

## `ConfigureEnvironment.ps1`

This script will provision a user's Azure PowerShell environment settings for Azure Government. To use it, simply launch a PowerShell console as an Administrator and execute the following command:

```powershell
.\ConfigureEnvironment.ps1
```

You can then download your `.publishsettings` file by running the following cmdlet:

```powershell
Get-AzurePublishSettingsFile -Environment AzureGovernmentCloud
```
