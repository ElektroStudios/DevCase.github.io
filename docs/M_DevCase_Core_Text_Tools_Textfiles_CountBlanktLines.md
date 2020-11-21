# Textfiles.CountBlanktLines Method 
 

Gets the total amount of blank lines of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int CountBlanktLines(
	string sourceFilepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Function CountBlanktLines ( 
	sourceFilepath As String,
	Optional enc As Encoding = Nothing
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As Textfiles
Dim sourceFilepath As String
Dim enc As Encoding
Dim returnValue As Integer

returnValue = instance.CountBlanktLines(sourceFilepath, 
	enc)
```

**C++**<br />
``` C++
public:
int CountBlanktLines(
	String^ sourceFilepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
member CountBlanktLines : 
        sourceFilepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: Int32<br />A value that contains the total amount of blank lines of the source textfile.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lineCount As Integer = CountBlanktLines("C:\file.txt", Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />