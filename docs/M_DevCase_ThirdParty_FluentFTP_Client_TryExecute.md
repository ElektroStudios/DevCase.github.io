# Client.TryExecute Method 
 

Tries to execute a command on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool TryExecute(
	string command
)
```

**VB**<br />
``` VB
Public Function TryExecute ( 
	command As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim command As String
Dim returnValue As Boolean

returnValue = instance.TryExecute(command)
```

**C++**<br />
``` C++
public:
bool TryExecute(
	String^ command
)
```

**F#**<br />
``` F#
member TryExecute : 
        command : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>command</dt><dd>Type: System.String<br />The command to execute on the FTP server.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if command execution successfull, otherwise returns `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />