# Textfiles.RemoveLines Method (String, String, IEnumerable(Int32), TextDirection, Encoding)
 

Removes the specified line numbers in the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveLines(
	string sourceFilepath,
	string targetFilepath,
	IEnumerable<int> lineNumbers,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveLines ( 
	sourceFilepath As String,
	targetFilepath As String,
	lineNumbers As IEnumerable(Of Integer),
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim lineNumbers As IEnumerable(Of Integer)
Dim textDirection As TextDirection
Dim enc As EncodingTextfiles.RemoveLines(sourceFilepath, 
	targetFilepath, lineNumbers, textDirection, 
	enc)
```

**C++**<br />
``` C++
public:
static void RemoveLines(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	IEnumerable<int>^ lineNumbers, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member RemoveLines : 
        sourceFilepath : string * 
        targetFilepath : string * 
        lineNumbers : IEnumerable<int> * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>lineNumbers</dt><dd>Type: System.Collections.Generic.IEnumerable(Int32)<br />The index of the lines to remove.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
RemoveLines("C:\old file.txt", "C:\new file.txt", {1, 2, 3}, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_RemoveLines">RemoveLines Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />