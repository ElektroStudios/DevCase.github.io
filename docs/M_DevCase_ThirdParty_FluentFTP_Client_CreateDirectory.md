# Client.CreateDirectory Method 
 

Creates a directory on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void CreateDirectory(
	string directorypath,
	bool force
)
```

**VB**<br />
``` VB
Public Sub CreateDirectory ( 
	directorypath As String,
	force As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim force As Boolean

instance.CreateDirectory(directorypath, 
	force)
```

**C++**<br />
``` C++
public:
void CreateDirectory(
	String^ directorypath, 
	bool force
)
```

**F#**<br />
``` F#
member CreateDirectory : 
        directorypath : string * 
        force : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The ftp directory path.</dd><dt>force</dt><dd>Type: System.Boolean<br />Try to force all non-existant pieces of the path to be created.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />