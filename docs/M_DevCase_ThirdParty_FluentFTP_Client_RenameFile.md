# Client.RenameFile Method 
 

Rename a file on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void RenameFile(
	string filepath,
	string newfilepath
)
```

**VB**<br />
``` VB
Public Sub RenameFile ( 
	filepath As String,
	newfilepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim filepath As String
Dim newfilepath As String

instance.RenameFile(filepath, newfilepath)
```

**C++**<br />
``` C++
public:
void RenameFile(
	String^ filepath, 
	String^ newfilepath
)
```

**F#**<br />
``` F#
member RenameFile : 
        filepath : string * 
        newfilepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The ftp file path.</dd><dt>newfilepath</dt><dd>Type: System.String<br />The new ftp file path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />