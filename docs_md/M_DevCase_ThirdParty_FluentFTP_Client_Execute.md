# Client.Execute Method 
 

Executes a command on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FtpReply Execute(
	string command
)
```

**VB**<br />
``` VB
Public Function Execute ( 
	command As String
) As FtpReply
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim command As String
Dim returnValue As FtpReply

returnValue = instance.Execute(command)
```

**C++**<br />
``` C++
public:
FtpReply Execute(
	String^ command
)
```

**F#**<br />
``` F#
member Execute : 
        command : string -> FtpReply 

```


#### Parameters
&nbsp;<dl><dt>command</dt><dd>Type: System.String<br />The command to execute on the server.</dd></dl>

#### Return Value
Type: FtpReply<br />Returns an object containing the server reply information.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />