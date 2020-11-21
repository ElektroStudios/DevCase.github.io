# Textfiles.TrimStart Method (String, Char[], Encoding)
 

Trims the specified chars from the start of the lines of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> TrimStart(
	string sourceFilepath,
	char[] trimChars = null,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function TrimStart ( 
	sourceFilepath As String,
	Optional trimChars As Char() = Nothing,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim trimChars As Char()
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.TrimStart(sourceFilepath, 
	trimChars, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ TrimStart(
	String^ sourceFilepath, 
	array<wchar_t>^ trimChars = nullptr, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member TrimStart : 
        sourceFilepath : string * 
        ?trimChars : char[] * 
        ?enc : Encoding 
(* Defaults:
        let _trimChars = defaultArg trimChars null
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>trimChars (Optional)</dt><dd>Type: System.Char[]<br />The characters to trim from lines.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the trimmed lines.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = TrimStart("C:\file.txt", {" "c, ControlChars.NullChar}, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_TrimStart">TrimStart Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />