# Textfiles.InsertLines Method (String, String, Int32, IEnumerable(String), TextDirection, Encoding)
 

Inserts the specified text-lines in the given line number of the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InsertLines(
	string sourceFilepath,
	string targetFilepath,
	int lineNumber,
	IEnumerable<string> textCol,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub InsertLines ( 
	sourceFilepath As String,
	targetFilepath As String,
	lineNumber As Integer,
	textCol As IEnumerable(Of String),
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim lineNumber As Integer
Dim textCol As IEnumerable(Of String)
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.InsertLines(sourceFilepath, 
	targetFilepath, lineNumber, textCol, 
	textDirection, enc)
```

**C++**<br />
``` C++
public:
static void InsertLines(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	int lineNumber, 
	IEnumerable<String^>^ textCol, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member InsertLines : 
        sourceFilepath : string * 
        targetFilepath : string * 
        lineNumber : int * 
        textCol : IEnumerable<string> * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The start index of the line to insert.</dd><dt>textCol</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The text-lines to insert.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
InsertLines("C:\old file.txt", "C:\new file.txt", 5, {"Text"}, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_InsertLines">InsertLines Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />