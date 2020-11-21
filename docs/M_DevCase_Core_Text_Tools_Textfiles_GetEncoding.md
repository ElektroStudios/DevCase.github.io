# Textfiles.GetEncoding Method (FileInfo)
 

Determines the Encoding of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Encoding GetEncoding(
	FileInfo sourceFile
)
```

**VB**<br />
``` VB
Public Shared Function GetEncoding ( 
	sourceFile As FileInfo
) As Encoding
```

**VB Usage**<br />
``` VB Usage
Dim sourceFile As FileInfo
Dim returnValue As Encoding

returnValue = Textfiles.GetEncoding(sourceFile)
```

**C++**<br />
``` C++
public:
static Encoding^ GetEncoding(
	FileInfo^ sourceFile
)
```

**F#**<br />
``` F#
static member GetEncoding : 
        sourceFile : FileInfo -> Encoding 

```


#### Parameters
&nbsp;<dl><dt>sourceFile</dt><dd>Type: System.IO.FileInfo<br />The source textfile.</dd></dl>

#### Return Value
Type: Encoding<br />If the encoding can be detected, the return value is the detected Encoding, if the encoding can't be detected, the return value is Default.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim encoding As Encoding = GetEncoding(New FileInfo("C:\file.txt"))
Dim encodingName As String = GetEncoding(New FileInfo("C:\file.txt")).WebName
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_GetEncoding">GetEncoding Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />