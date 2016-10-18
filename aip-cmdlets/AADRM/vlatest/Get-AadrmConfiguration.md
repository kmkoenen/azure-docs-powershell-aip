---
external help file: Microsoft.RightsManagementServices.Online.Admin.PowerShell.dll-Help.xml
online version: http://go.microsoft.com/fwlink/?LinkId=400608
schema: 2.0.0
---

# Get-AadrmConfiguration

## SYNOPSIS
Gets the Rights Management configuration of your tenant.

## SYNTAX

```
Get-AadrmConfiguration [<CommonParameters>]
```

## DESCRIPTION
The Get-AadrmConfiguration cmdlet gets the current Rights Management configuration of your tenant.

## EXAMPLES

### Example 1: Display Rights Management  configuration
```
PS C:\>Get-AadrmConfiguration
BPOSId                                    : 9c11c87a-ac8b-46a3-8d5c-f4d0b72ee29a

RightsManagementServiceId                 : 5c6bb73b-1038-4eec-863d-49bded473437

LicensingIntranetDistributionPointUrl     : https://5c6bb73b-1038-4eec-863d-49bded473437.rms.na.aadrm.com/_wmcs/licensing

LicensingExtranetDistributionPointUrl     : https://5c6bb73b-1038-4eec-863d-49bded473437.rms.na.aadrm.com/_wmcs/licensing

CertificationIntranetDistributionPointUrl : https://5c6bb73b-1038-4eec-863d-49bded473437.rms.na.aadrm.com/_wmcs/certification

CertificationExtranetDistributionPointUrl: https://5c6bb73b-1038-4eec-863d-49bded473437.rms.na.aadrm.com/_wmcs/certification

AdminConnectionUrl                        : https://admin.na.aadrm.com/admin/admin.svc/Tenants/ 5c6bb73b-1038-4eec-863d-49bded473437

OnPremiseDomainName                       : 

Keys                                      : {c46b5d49-1c4c-4a79-83d1-ec12a25f3134}

CurrentLicensorCertificateGuid            : c46b5d49-1c4c-4a79-83d1-ec12a25f3134

Templates                                 : { c46b5d49-1c4c-4a79-83d1-ec12a25f3134, 

                                            5c6d36g9-c24e-4222-7786e-b1a8a1ecab60}

FunctionalState                           : Enabled

SuperUsersEnabled                         : Disabled

SuperUsers                                : {admin3@contoso.com, admin4@contoso.com}

AdminRoleMembers                          : {Global Administrator -> 5834f4d6-35d2-455b-a134-75d4cdc82172, 

                                            ConnectorAdministrator -> 5834f4d6-35d2-455b-a134-75d4cdc82172}

KeyRolloverCount                          : 0

ProvisioningDate                          : 1/30/2014 9:01:31 PM

IPCv3ServiceFunctionalState               : Enabled

DevicePlatformState                       : {Windows -> True, WindowsStore -> True, WindowsPhone -> True, Mac ->
```

This command displays the current Rights Management configuration for your organization.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
