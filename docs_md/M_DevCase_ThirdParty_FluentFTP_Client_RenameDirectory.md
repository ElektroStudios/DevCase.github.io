# Client.RenameDirectory Method 
 

Rename a directory on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void RenameDirectory(
	string directorypath,
	string newdirectorypath
)
```

**VB**<br />
``` VB
Public Sub RenameDirectory ( 
	directorypath As String,
	newdirectorypath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim newdirectorypath As String

instance.RenameDirectory(directorypath, 
	newdirectorypath)
```

**C++**<br />
``` C++
public:
void RenameDirectory(
	String^ directorypath, 
	String^ newdirectorypath
)
```

**F#**<br />
``` F#
member RenameDirectory : 
        directorypath : string * 
        newdirectorypath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The ftp file path.</dd><dt>newdirectorypath</dt><dd>Type: System.String<br />The new ftp file path.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />