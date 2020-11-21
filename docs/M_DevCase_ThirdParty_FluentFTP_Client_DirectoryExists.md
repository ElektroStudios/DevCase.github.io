# Client.DirectoryExists Method 
 

Checks if a directory exist on the FTP server.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool DirectoryExists(
	string directorypath
)
```

**VB**<br />
``` VB
Public Function DirectoryExists ( 
	directorypath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim returnValue As Boolean

returnValue = instance.DirectoryExists(directorypath)
```

**C++**<br />
``` C++
public:
bool DirectoryExists(
	String^ directorypath
)
```

**F#**<br />
``` F#
member DirectoryExists : 
        directorypath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The ftp directory path.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.DirectoryExists(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />