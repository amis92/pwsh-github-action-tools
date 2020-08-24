# Invoke-ActionGroup
```

NAME
    Invoke-ActionGroup
    
SYNOPSIS
    Executes the argument script block within an output group.
    Equivalent of `core.group(name, func)`.
    
    
SYNTAX
    Invoke-ActionGroup [-Name] <String> [-ScriptBlock] <ScriptBlock> [<CommonParameters>]
    
    
DESCRIPTION
    

PARAMETERS
    -Name <String>
        Name of the output group.
        
        Required?                    true
        Position?                    1
        Default value                
        Accept pipeline input?       false
        Accept wildcard characters?  false
        
    -ScriptBlock <ScriptBlock>
        Script block to execute in between opening and closing output group.
        
        Required?                    true
        Position?                    2
        Default value                
        Accept pipeline input?       false
        Accept wildcard characters?  false
        
    <CommonParameters>
        This cmdlet supports the common parameters: Verbose, Debug,
        ErrorAction, ErrorVariable, WarningAction, WarningVariable,
        OutBuffer, PipelineVariable, and OutVariable. For more information, see
        about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216). 
    
INPUTS
    
OUTPUTS
    
    
RELATED LINKS
    https://github.com/actions/toolkit/blob/7f7e22a9406f546f9084e9eb7a4e541a3563f92b/docs/commands.md#group-and-ungroup-log-lines
    https://github.com/actions/toolkit/tree/7f7e22a9406f546f9084e9eb7a4e541a3563f92b/packages/core#logging

```
