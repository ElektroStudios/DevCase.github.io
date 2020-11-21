# HostsUtil.Add Method (Boolean, String, String, String)
 

Adds a new mapping in the Hosts file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Add(
	bool enabled,
	string hostName,
	string ip,
	string comment = null
)
```

**VB**<br />
``` VB
Public Shared Sub Add ( 
	enabled As Boolean,
	hostName As String,
	ip As String,
	Optional comment As String = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim enabled As Boolean
Dim hostName As String
Dim ip As String
Dim comment As StringHostsUtil.Add(enabled, hostName, ip, comment)
```

**C++**<br />
``` C++
public:
static void Add(
	bool enabled, 
	String^ hostName, 
	String^ ip, 
	String^ comment = nullptr
)
```

**F#**<br />
``` F#
static member Add : 
        enabled : bool * 
        hostName : string * 
        ip : string * 
        ?comment : string 
(* Defaults:
        let _comment = defaultArg comment null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>enabled</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), enables the mapping.</dd><dt>hostName</dt><dd>Type: System.String<br />The hostname.</dd><dt>ip</dt><dd>Type: System.String<br />The Ip address.</dd><dt>comment (Optional)</dt><dd>Type: System.String<br />A comment for this mapping.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td>Hosts file not found.</td></tr><tr><td>FormatException</td><td>Invalid Ip adress.</td></tr><tr><td>Exception</td><td>Hostname is already mapped.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_HostsUtil">HostsUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_HostsUtil_Add">Add Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />