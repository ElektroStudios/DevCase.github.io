# Client.GetModifiedTime Method 
 

Gets the modified time of file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DateTime GetModifiedTime(
	string filepath
)
```

**VB**<br />
``` VB
Public Function GetModifiedTime ( 
	filepath As String
) As DateTime
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim filepath As String
Dim returnValue As DateTime

returnValue = instance.GetModifiedTime(filepath)
```

**C++**<br />
``` C++
public:
DateTime GetModifiedTime(
	String^ filepath
)
```

**F#**<br />
``` F#
member GetModifiedTime : 
        filepath : string -> DateTime 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The ftp file path.</dd></dl>

#### Return Value
Type: DateTime<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.GetModifiedTime(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />