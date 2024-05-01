---
external help file: Microsoft.Windows.Bcd.Cmdlets.dll-Help.xml
Module Name: Microsoft.Windows.Bcd.Cmdlets
ms.date: 02/21/2024
online version: https://learn.microsoft.com/powershell/module/microsoft.windows.bcd.cmdlets/new-bcdstore?view=windowsserver2025-ps&wt.mc_id=ps-gethelp
schema: 2.0.0
title: New-BcdStore
---

# New-BcdStore

## SYNOPSIS
Creates a empty boot configuration data store. The created store is not a system store.  Similer to bcdedit /createstore

## SYNTAX

```
### NormalMode (Default)
New-BcdStore [-Path] <String> [-Force] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Creates a empty boot configuration data store and saves it in the path specified. BCD entries can be added to the store by using the New-Bcdentry command.

## EXAMPLES

### Example 1
```powershell
PS C:\WINDOWS\system32> New-BcdStore -Path C:\temp\bcd
```

This creates a empty boot configuration data store and saves it in the path specified. 

## PARAMETERS

### -Force
{{ Fill Force Description }}

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Path
Path the BCD file is saved to. 

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### Microsoft.Windows.Bcd.Cmdlets.BcdExtensions.BcdStoreInfo

## NOTES

## RELATED LINKS
