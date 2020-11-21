# HostsUtil.IsDisabled Method (HostsMappingInfo)
 

Checks whether a HostName is already disabled.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsDisabled(
	HostsMappingInfo mappingInfo
)
```

**VB**<br />
``` VB
Public Shared Function IsDisabled ( 
	mappingInfo As HostsMappingInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim mappingInfo As HostsMappingInfo
Dim returnValue As Boolean

returnValue = HostsUtil.IsDisabled(mappingInfo)
```

**C++**<br />
``` C++
public:
static bool IsDisabled(
	HostsMappingInfo^ mappingInfo
)
```

**F#**<br />
``` F#
static member IsDisabled : 
        mappingInfo : HostsMappingInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>mappingInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_HostsMappingInfo">DevCase.Core.Shell.HostsMappingInfo</a><br />A <a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a> instance containing the mapping info.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified Hostname is mapped; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_HostsUtil_IsDisabled">IsDisabled Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />