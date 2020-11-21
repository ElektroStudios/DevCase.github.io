# Textfiles.ReplaceLine Method (String, String, Int32, String, TextDirection, Encoding)
 

Replaces the specified line number in the source textfile with the given text-line, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ReplaceLine(
	string sourceFilepath,
	string targetFilepath,
	int lineNumber,
	string line,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub ReplaceLine ( 
	sourceFilepath As String,
	targetFilepath As String,
	lineNumber As Integer,
	line As String,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim lineNumber As Integer
Dim line As String
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.ReplaceLine(sourceFilepath, 
	targetFilepath, lineNumber, line, 
	textDirection, enc)
```

**C++**<br />
``` C++
public:
static void ReplaceLine(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	int lineNumber, 
	String^ line, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member ReplaceLine : 
        sourceFilepath : string * 
        targetFilepath : string * 
        lineNumber : int * 
        line : string * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The index of the line to replace.</dd><dt>line</dt><dd>Type: System.String<br />The text-line to replace.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ReplaceLine("C:\old file.txt", "C:\new file.txt", 5, "Text", Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_ReplaceLine">ReplaceLine Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />