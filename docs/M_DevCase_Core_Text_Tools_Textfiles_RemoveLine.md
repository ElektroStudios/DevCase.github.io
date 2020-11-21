# Textfiles.RemoveLine Method (String, Int32, TextDirection, Encoding)
 

Removes the specified line number in the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> RemoveLine(
	string sourceFilepath,
	int lineNumber,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function RemoveLine ( 
	sourceFilepath As String,
	lineNumber As Integer,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim lineNumber As Integer
Dim textDirection As TextDirection
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.RemoveLine(sourceFilepath, 
	lineNumber, textDirection, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ RemoveLine(
	String^ sourceFilepath, 
	int lineNumber, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member RemoveLine : 
        sourceFilepath : string * 
        lineNumber : int * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>lineNumber</dt><dd>Type: System.Int32<br />The index of the line to remove.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the textfile lines less the removed line.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = RemoveLine("C:\file.txt", 5, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_RemoveLine">RemoveLine Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />