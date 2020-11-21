# Client Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_FluentFTP_Client">Client</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Client(
	string host,
	string username,
	string pass
)
```

**VB**<br />
``` VB
Public Sub New ( 
	host As String,
	username As String,
	pass As String
)
```

**VB Usage**<br />
``` VB Usage
Dim host As String
Dim username As String
Dim pass As String

Dim instance As New Client(host, username, 
	pass)
```

**C++**<br />
``` C++
public:
Client(
	String^ host, 
	String^ username, 
	String^ pass
)
```

**F#**<br />
``` F#
new : 
        host : string * 
        username : string * 
        pass : string -> Client
```


#### Parameters
&nbsp;<dl><dt>host</dt><dd>Type: System.String<br />The ftp site.</dd><dt>username</dt><dd>Type: System.String<br />FTP account name.</dd><dt>pass</dt><dd>Type: System.String<br />The FTP account password.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />