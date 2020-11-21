# Client.GetFileSize Method 
 

Gets the size of file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public long GetFileSize(
	string filepath
)
```

**VB**<br />
``` VB
Public Function GetFileSize ( 
	filepath As String
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim filepath As String
Dim returnValue As Long

returnValue = instance.GetFileSize(filepath)
```

**C++**<br />
``` C++
public:
long long GetFileSize(
	String^ filepath
)
```

**F#**<br />
``` F#
member GetFileSize : 
        filepath : string -> int64 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The ftp file path.</dd></dl>

#### Return Value
Type: Int64<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.GetFileSize(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />