# Textfiles.ReplaceLine Method (String, Int32, String, TextDirection, Encoding)
 

Replaces the specified line number in the source textfile with the given text-line.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> ReplaceLine(
	string sourceFilepath,
	int lineNumber,
	string text,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function ReplaceLine ( 
	sourceFilepath As String,
	lineNumber As Integer,
	text As String,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim lineNumber As Integer
Dim text As String
Dim textDirection As TextDirection
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.ReplaceLine(sourceFilepath, 
	lineNumber, text, textDirection, 
	enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ ReplaceLine(
	String^ sourceFilepath, 
	int lineNumber, 
	String^ text, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReplaceLine : 
        sourceFilepath : string * 
        lineNumber : int * 
        text : string * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The index of the line to replace.</dd><dt>text</dt><dd>Type: System.String<br />The text-line to replace.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the textfile lines with the replaced line.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = ReplaceLine("C:\file.txt", 5, "Text", Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_ReplaceLine">ReplaceLine Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />