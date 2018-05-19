---
external help file: PSFramework-help.xml
Module Name: PSFramework
online version:
schema: 2.0.0
---

# Import-PSFConfig

## SYNOPSIS
Imports a json configuration file into the configuration system.

## SYNTAX

```
Import-PSFConfig [-Path] <String[]> [[-IncludeFilter] <String[]>] [[-ExcludeFilter] <String[]>] [-Peek]
 [-EnableException] [<CommonParameters>]
```

## DESCRIPTION
Imports a json configuration file into the configuration system.

## EXAMPLES

### EXAMPLE 1
```
Import-PSFConfig -Path '.\config.json'
```

Imports the configuration stored in '.\config.json'

## PARAMETERS

### -Path
The path to the json file to import.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IncludeFilter
If specified, only elements with names that are similar (-like) to names in this list will be imported.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExcludeFilter
Elements that are similar (-like) to names in this list will not be imported.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Peek
Rather than applying the setting, return the configuration items that would have been applied.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableException
This parameters disables user-friendly warnings and enables the throwing of exceptions.
This is less user friendly, but allows catching exceptions in calling scripts.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS