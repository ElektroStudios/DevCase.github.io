# Textfiles.RemoveLine Method (String, String, Int32, TextDirection, Encoding)
 

Removes the specified line number in the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveLine(
	string sourceFilepath,
	string targetFilepath,
	int lineNumber,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveLine ( 
	sourceFilepath As String,
	targetFilepath As String,
	lineNumber As Integer,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim lineNumber As Integer
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.RemoveLine(sourceFilepath, 
	targetFilepath, lineNumber, textDirection, 
	enc)
```

**C++**<br />
``` C++
public:
static void RemoveLine(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	int lineNumber, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member RemoveLine : 
        sourceFilepath : string * 
        targetFilepath : string * 
        lineNumber : int * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The index of the line to remove.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
RemoveLine("C:\old file.txt", "C:\new file.txt", 5, TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_RemoveLine">RemoveLine Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />