# Textfiles.InsertLine Method (String, Int32, String, TextDirection, Encoding)
 

Inserts the specified text-line in the given line number of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> InsertLine(
	string sourceFilepath,
	int lineNumber,
	string text,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function InsertLine ( 
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

returnValue = Textfiles.InsertLine(sourceFilepath, 
	lineNumber, text, textDirection, 
	enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ InsertLine(
	String^ sourceFilepath, 
	int lineNumber, 
	String^ text, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member InsertLine : 
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
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The start index of the line to insert.</dd><dt>text</dt><dd>Type: System.String<br />The text-line to insert.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the textfile lines with the inserted line.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>lineNumber</td></tr><tr><td>InvalidEnumArgumentException</td><td>textDirection</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = InsertLine("C:\old file.txt", "C:\new file.txt", 5, "Text", Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_InsertLine">InsertLine Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />