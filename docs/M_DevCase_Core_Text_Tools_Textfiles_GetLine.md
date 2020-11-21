# Textfiles.GetLine Method 
 

Gets the specified line number from the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetLine(
	string sourceFilepath,
	int lineNumber,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function GetLine ( 
	sourceFilepath As String,
	lineNumber As Integer,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim lineNumber As Integer
Dim textDirection As TextDirection
Dim enc As Encoding
Dim returnValue As String

returnValue = Textfiles.GetLine(sourceFilepath, 
	lineNumber, textDirection, enc)
```

**C++**<br />
``` C++
public:
static String^ GetLine(
	String^ sourceFilepath, 
	int lineNumber, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member GetLine : 
        sourceFilepath : string * 
        lineNumber : int * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The index of the line to get.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: String<br />A String that contains the text of the obtained line.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>lineNumber</td></tr><tr><td>InvalidEnumArgumentException</td><td>textDirection</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim line As String = GetLine("C:\file.txt", 5, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />