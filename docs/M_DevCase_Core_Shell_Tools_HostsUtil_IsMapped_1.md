# HostsUtil.IsMapped Method (String)
 

Checks whether a HostName is already mapped.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsMapped(
	string hostName
)
```

**VB**<br />
``` VB
Public Shared Function IsMapped ( 
	hostName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hostName As String
Dim returnValue As Boolean

returnValue = HostsUtil.IsMapped(hostName)
```

**C++**<br />
``` C++
public:
static bool IsMapped(
	String^ hostName
)
```

**F#**<br />
``` F#
static member IsMapped : 
        hostName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hostName</dt><dd>Type: System.String<br />The hostname.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified Hostname is mapped; otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Hosts file not found.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_HostsUtil_IsMapped">IsMapped Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />