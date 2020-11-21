# Client.OpenRead Method 
 

Opens the specified file for reading.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Stream OpenRead(
	string filepath
)
```

**VB**<br />
``` VB
Public Function OpenRead ( 
	filepath As String
) As Stream
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim filepath As String
Dim returnValue As Stream

returnValue = instance.OpenRead(filepath)
```

**C++**<br />
``` C++
public:
Stream^ OpenRead(
	String^ filepath
)
```

**F#**<br />
``` F#
member OpenRead : 
        filepath : string -> Stream 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The ftp file path.</dd></dl>

#### Return Value
Type: Stream<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.OpenRead(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />