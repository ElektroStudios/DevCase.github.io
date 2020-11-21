# Textfiles.ReplaceLines Method (String, String, IEnumerable(Int32), String, TextDirection, Encoding)
 

Replaces the specified line numbesr in the source textfile with the given text-line, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ReplaceLines(
	string sourceFilepath,
	string targetFilepath,
	IEnumerable<int> lineNumbers,
	string text,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub ReplaceLines ( 
	sourceFilepath As String,
	targetFilepath As String,
	lineNumbers As IEnumerable(Of Integer),
	text As String,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim lineNumbers As IEnumerable(Of Integer)
Dim text As String
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.ReplaceLines(sourceFilepath, 
	targetFilepath, lineNumbers, text, 
	textDirection, enc)
```

**C++**<br />
``` C++
public:
static void ReplaceLines(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	IEnumerable<int>^ lineNumbers, 
	String^ text, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReplaceLines : 
        sourceFilepath : string * 
        targetFilepath : string * 
        lineNumbers : IEnumerable<int> * 
        text : string * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>lineNumbers</dt><dd>Type: System.Collections.Generic.IEnumerable(Int32)<br />The index of the lines to replace.</dd><dt>text</dt><dd>Type: System.String<br />The text-line to replace.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ReplaceLines("C:\old file.txt", "C:\new file.txt", {1, 2, 3}, "Text", Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_ReplaceLines">ReplaceLines Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />