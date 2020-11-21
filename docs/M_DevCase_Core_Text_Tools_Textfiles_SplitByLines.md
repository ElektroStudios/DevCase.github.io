# Textfiles.SplitByLines Method 
 

Splits the source textfile by the specified amount of lines.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<IEnumerable<string>> SplitByLines(
	string sourceFilepath,
	int amountOfLines,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function SplitByLines ( 
	sourceFilepath As String,
	amountOfLines As Integer,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of IEnumerable(Of String))
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim amountOfLines As Integer
Dim enc As Encoding
Dim returnValue As IEnumerable(Of IEnumerable(Of String))

returnValue = Textfiles.SplitByLines(sourceFilepath, 
	amountOfLines, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<IEnumerable<String^>^>^ SplitByLines(
	String^ sourceFilepath, 
	int amountOfLines, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member SplitByLines : 
        sourceFilepath : string * 
        amountOfLines : int * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<IEnumerable<string>> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>amountOfLines</dt><dd>Type: System.Int32<br />The amount of lines.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(IEnumerable(String))<br />An IEnumerable(T) that contains the splitted parts.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim parts As IEnumerable(Of IEnumerable(Of String)) = SplitByLines("C:\file.txt", 2, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />