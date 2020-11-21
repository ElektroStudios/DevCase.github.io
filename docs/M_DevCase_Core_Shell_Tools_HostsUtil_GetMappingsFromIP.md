# HostsUtil.GetMappingsFromIP Method 
 

Gets a List(T) instance containing the mapping info of all mappings matching the specified IP address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<HostsMappingInfo> GetMappingsFromIP(
	string ip
)
```

**VB**<br />
``` VB
Public Shared Function GetMappingsFromIP ( 
	ip As String
) As List(Of HostsMappingInfo)
```

**VB Usage**<br />
``` VB Usage
Dim ip As String
Dim returnValue As List(Of HostsMappingInfo)

returnValue = HostsUtil.GetMappingsFromIP(ip)
```

**C++**<br />
``` C++
public:
static List<HostsMappingInfo^>^ GetMappingsFromIP(
	String^ ip
)
```

**F#**<br />
``` F#
static member GetMappingsFromIP : 
        ip : string -> List<HostsMappingInfo> 

```


#### Parameters
&nbsp;<dl><dt>ip</dt><dd>Type: System.String<br />\[Missing <param name="ip"/> documentation for "M:DevCase.Core.Shell.Tools.HostsUtil.GetMappingsFromIP(System.String)"\]</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_Core_Shell_HostsMappingInfo">HostsMappingInfo</a>)<br />\[Missing <returns> documentation for "M:DevCase.Core.Shell.Tools.HostsUtil.GetMappingsFromIP(System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Hosts file not found.</td></tr><tr><td>FormatException</td><td>Invalid IP adress.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />