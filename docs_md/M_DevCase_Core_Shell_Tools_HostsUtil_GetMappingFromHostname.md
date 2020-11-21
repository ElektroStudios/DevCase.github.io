# HostsUtil.GetMappingFromHostname Method 
 

Gets a <a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a> instance containing the mapping info of a hostname.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static HostsMappingInfo GetMappingFromHostname(
	string hostname
)
```

**VB**<br />
``` VB
Public Shared Function GetMappingFromHostname ( 
	hostname As String
) As HostsMappingInfo
```

**VB Usage**<br />
``` VB Usage
Dim hostname As String
Dim returnValue As HostsMappingInfo

returnValue = HostsUtil.GetMappingFromHostname(hostname)
```

**C++**<br />
``` C++
public:
static HostsMappingInfo^ GetMappingFromHostname(
	String^ hostname
)
```

**F#**<br />
``` F#
static member GetMappingFromHostname : 
        hostname : string -> HostsMappingInfo 

```


#### Parameters
&nbsp;<dl><dt>hostname</dt><dd>Type: System.String<br />\[Missing <param name="hostname"/> documentation for "M:DevCase.Core.Shell.Tools.HostsUtil.GetMappingFromHostname(System.String)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a><br />\[Missing <returns> documentation for "M:DevCase.Core.Shell.Tools.HostsUtil.GetMappingFromHostname(System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Hosts file not found.</td></tr><tr><td>Exception</td><td>Hostname is not mapped.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />