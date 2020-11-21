# Textfiles.GetEncoding Method (String)
 

Determines the Encoding of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Encoding GetEncoding(
	string sourceFilepath
)
```

**VB**<br />
``` VB
Public Shared Function GetEncoding ( 
	sourceFilepath As String
) As Encoding
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim returnValue As Encoding

returnValue = Textfiles.GetEncoding(sourceFilepath)
```

**C++**<br />
``` C++
public:
static Encoding^ GetEncoding(
	String^ sourceFilepath
)
```

**F#**<br />
``` F#
static member GetEncoding : 
        sourceFilepath : string -> Encoding 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd></dl>

#### Return Value
Type: Encoding<br />If the encoding can be detected, the return value is the detected Encoding, if the encoding can't be detected, the return value is Default.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encoding As Encoding = GetEncoding("C:\file.txt")
Dim encodingName As String = GetEncoding("C:\file.txt").WebName
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_GetEncoding">GetEncoding Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />