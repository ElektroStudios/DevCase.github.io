# Textfiles.Randomize Method (String, Encoding)
 

Randomizes the lines of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> Randomize(
	string sourceFilepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Randomize ( 
	sourceFilepath As String,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.Randomize(sourceFilepath, 
	enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ Randomize(
	String^ sourceFilepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Randomize : 
        sourceFilepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the randomized lines.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = Randomize("C:\file.txt", Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Randomize">Randomize Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />