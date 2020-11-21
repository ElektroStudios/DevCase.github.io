# Client.GetNameListing Method 
 

Returns a file/directory listing using the NLST command.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string[] GetNameListing(
	string directorypath
)
```

**VB**<br />
``` VB
Public Function GetNameListing ( 
	directorypath As String
) As String()
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim directorypath As String
Dim returnValue As String()

returnValue = instance.GetNameListing(directorypath)
```

**C++**<br />
``` C++
public:
array<String^>^ GetNameListing(
	String^ directorypath
)
```

**F#**<br />
``` F#
member GetNameListing : 
        directorypath : string -> string[] 

```


#### Parameters
&nbsp;<dl><dt>directorypath</dt><dd>Type: System.String<br />The directory path on the FTP.</dd></dl>

#### Return Value
Type: String[]<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.GetNameListing(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />