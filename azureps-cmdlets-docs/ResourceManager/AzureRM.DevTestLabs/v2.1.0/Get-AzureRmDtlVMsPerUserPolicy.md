---
external help file: Microsoft.Azure.Commands.DevTestLabs.dll-Help.xml
online version: .\Set-AzureRmDtlVMsPerUserPolicy.md
schema: 2.0.0
ms.assetid: C985E534-03ED-4370-BBCD-1E918563A65D
---

# Get-AzureRmDtlVMsPerUserPolicy

## SYNOPSIS
Gets the virtual machines per user policy of a lab in DevTest Labs.

## SYNTAX

```
Get-AzureRmDtlVMsPerUserPolicy [-LabName] <String> [-ResourceGroupName] <String>
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmDtlVMsPerUserPolicy** cmdlet gets the virtual machines per user policy of a lab, which allows you to set the maximum number of virtual machines allowed per user.
The cmdlet returns the enabled or disabled status of the policy and the maximum number of virtual machines allowed per user that you have set in the policy.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -LabName
Specifies the name of the lab for which this cmdlet gets the virtual machine per user policy.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group that the lab belongs to.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.Commands.DevTestLabs.Models.PSPolicy
This cmdlet returns the policy that specifies the maximum number of virtual machines that can be created by a user in the lab.

## NOTES

## RELATED LINKS

[Set-AzureRmDtlVMsPerUserPolicy](.\Set-AzureRmDtlVMsPerUserPolicy.md)

