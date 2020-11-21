# Textfiles.SkipLines Method (String, Int32, TextDirection, Encoding)
 

Skips the specified amount of lines in the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> SkipLines(
	string sourceFilepath,
	int amountOfLines,
	TextDirection textDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function SkipLines ( 
	sourceFilepath As String,
	amountOfLines As Integer,
	textDirection As TextDirection,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim amountOfLines As Integer
Dim textDirection As TextDirection
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.SkipLines(sourceFilepath, 
	amountOfLines, textDirection, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ SkipLines(
	String^ sourceFilepath, 
	int amountOfLines, 
	TextDirection textDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member SkipLines : 
        sourceFilepath : string * 
        amountOfLines : int * 
        textDirection : TextDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>amountOfLines</dt><dd>Type: System.Int32<br />The amount of lines to skip.</dd><dt>textDirection</dt><dd>Type: <a href="T_DevCase_Core_Text_TextDirection">DevCase.Core.Text.TextDirection</a><br />The text direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the non-skipped lines.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>amountOfLines</td></tr><tr><td>InvalidEnumArgumentException</td><td>textDirection</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = SkipLines("C:\file.txt", 5, Textfiles.TextDirection.Top, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_SkipLines">SkipLines Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />