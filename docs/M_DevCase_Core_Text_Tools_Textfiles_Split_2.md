# Textfiles.Split Method (String, IEnumerable(String), StringSplitOptions, Encoding)
 

Splits the source textfile by the specified strings.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> Split(
	string sourceFilepath,
	IEnumerable<string> strCol,
	StringSplitOptions splitOptions = StringSplitOptions.None,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Split ( 
	sourceFilepath As String,
	strCol As IEnumerable(Of String),
	Optional splitOptions As StringSplitOptions = StringSplitOptions.None,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim strCol As IEnumerable(Of String)
Dim splitOptions As StringSplitOptions
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.Split(sourceFilepath, 
	strCol, splitOptions, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ Split(
	String^ sourceFilepath, 
	IEnumerable<String^>^ strCol, 
	StringSplitOptions splitOptions = StringSplitOptions::None, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Split : 
        sourceFilepath : string * 
        strCol : IEnumerable<string> * 
        ?splitOptions : StringSplitOptions * 
        ?enc : Encoding 
(* Defaults:
        let _splitOptions = defaultArg splitOptions StringSplitOptions.None
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>strCol</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The strings that delimits the split.</dd><dt>splitOptions (Optional)</dt><dd>Type: System.StringSplitOptions<br />The split behavior option.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the splitted lines.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = Split("C:\file.txt", {"Hello World"}, StringSplitOptions.RemoveEmptyEntries, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Split">Split Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />