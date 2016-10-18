---
external help file: Microsoft.RightsManagementServices.Online.Admin.PowerShell.dll-Help.xml
online version: http://go.microsoft.com/fwlink/?LinkId=722837
schema: 2.0.0
---

# Get-AadrmSuperUserGroup

## SYNOPSIS
Gets the super user group for Rights Management.

## SYNTAX

```
Get-AadrmSuperUserGroup [<CommonParameters>]
```

## DESCRIPTION
The Get-AadrmSuperUserGroup cmdlet gets the email address of the Azure Rights Management super user group for your organization.
This cmdlet does not get users that are individually assigned as super users with the Add-AadrmSuperUser cmdlet.

For more information about super users, see Configuring super users for Azure Rights Management and discovery services or data recovery (https://docs.microsoft.com/rights-management/deploy-use/configure-super-users) on the Microsoft documentation site.

## EXAMPLES

### Example 1: Get the super user group
```
PS C:\>Get-AadrmSuperUserGroup
```

This command gets the email address of the super user group for an organization.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.String
This operation returns the super user group email address as a String.
If no super user group exists, an empty String is returned.

## NOTES

## RELATED LINKS

[Add-AadrmSuperUser]()

[Clear-AadrmSuperUserGroup]()

[Set-AadrmSuperUserGroup]()
