# Textfiles.SkipLines Method (String, String, Int32, TextDirection, Encoding)
 

Skips the specified amount of lines in the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SkipLines(
	string sourceFilepath,
	string targetFilepath,
	int amountOfLines,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub SkipLines ( 
	sourceFilepath As String,
	targetFilepath As String,
	amountOfLines As Integer,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim amountOfLines As Integer
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.SkipLines(sourceFilepath, targetFilepath, 
	amountOfLines, textDirection, enc)
```

**C++**<br />
``` C++
public:
static void SkipLines(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	int amountOfLines, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member SkipLines : 
        sourceFilepath : string * 
        targetFilepath : string * 
        amountOfLines : int * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>amountOfLines</dt><dd>Type: System.Int32<br />The amount of lines to skip.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SkipLines("C:\old file.txt", "C:\new file.txt", 5, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_SkipLines">SkipLines Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />