# FreeImageUtil.GetFormat Method 
 

Gets the format of the specified image file.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetFormat(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function GetFormat ( 
	filepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As String

returnValue = FreeImageUtil.GetFormat(filepath)
```

**C++**<br />
``` C++
public:
static String^ GetFormat(
	String^ filepath
)
```

**F#**<br />
``` F#
static member GetFormat : 
        filepath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The image filepath.</dd></dl>

#### Return Value
Type: String<br />The format of the specified image file.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FreeImage_FreeImageUtil">FreeImageUtil Class</a><br /><a href="N_DevCase_ThirdParty_FreeImage">DevCase.ThirdParty.FreeImage Namespace</a><br />