# HostsUtil.Remove Method (String)
 

Removes a mapping.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Remove(
	string hostName
)
```

**VB**<br />
``` VB
Public Shared Sub Remove ( 
	hostName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim hostName As StringHostsUtil.Remove(hostName)
```

**C++**<br />
``` C++
public:
static void Remove(
	String^ hostName
)
```

**F#**<br />
``` F#
static member Remove : 
        hostName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>hostName</dt><dd>Type: System.String<br />The hostname.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Hosts file not found.</td></tr><tr><td>Exception</td><td>Hostname is not mapped.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_HostsUtil_Remove">Remove Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />