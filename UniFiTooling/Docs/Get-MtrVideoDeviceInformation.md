﻿# Get-MtrVideoDeviceInformation

## SYNOPSIS
Get information about all attached Video devices

## SYNTAX

### Set 1
```
Get-MtrVideoDeviceInformation [[-Computer] <String>] [-DeviceID] [<CommonParameters>]
```

## DESCRIPTION
Get information about all attached Video devices

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
PS C:\\\>
```powershell
Get-MtrVideoDeviceInformation
```

### -------------------------- EXAMPLE 2 --------------------------
PS C:\\\>
```powershell
Get-MtrVideoDeviceInformation -Computer 'RanierConf'
```

## PARAMETERS

### Computer
The Computer to get the information from, default is the localhost

```yaml
Type: String
Parameter Sets: Set 1
Aliases: MtrDevice

Required: false
Position: 0
Default Value: $env:COMPUTERNAME
Pipeline Input: True (ByPropertyName, ByValue)
```

### DeviceID
Get the DeviceID attribute of the Video devices.
Might be useful if you need the ID for the content camera.

```yaml
Type: SwitchParameter
Parameter Sets: Set 1
Aliases: VideoDeviceID

Required: false
Position: named
Default Value: False
Pipeline Input: True (ByPropertyName, ByValue)
```

### \<CommonParameters\>
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String


### System.Management.Automation.SwitchParameter


## OUTPUTS

## NOTES

Initial Version

## RELATED LINKS

[Online version:](https://docs.microsoft.com/en-us/MicrosoftTeams/rooms/rooms-operations)


*Generated by: PowerShell HelpWriter 2020 v2.3.46*