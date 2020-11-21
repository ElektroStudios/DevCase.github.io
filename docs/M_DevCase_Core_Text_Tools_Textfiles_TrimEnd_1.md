# Textfiles.TrimEnd Method (String, String, Char[], Encoding)
 

Trims the specified chars from the end of the lines of the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void TrimEnd(
	string sourceFilepath,
	string targetFilepath,
	char[] trimChars = null,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub TrimEnd ( 
	sourceFilepath As String,
	targetFilepath As String,
	Optional trimChars As Char() = Nothing,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim trimChars As Char()
Dim enc As EncodingTextfiles.TrimEnd(sourceFilepath, targetFilepath, 
	trimChars, enc)
```

**C++**<br />
``` C++
public:
static void TrimEnd(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	array<wchar_t>^ trimChars = nullptr, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member TrimEnd : 
        sourceFilepath : string * 
        targetFilepath : string * 
        ?trimChars : char[] * 
        ?enc : Encoding 
(* Defaults:
        let _trimChars = defaultArg trimChars null
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>trimChars (Optional)</dt><dd>Type: System.Char[]<br />The characters to trim from lines.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
TrimEnd("C:\old file.txt", "C:\new file.txt", {" "c, ControlChars.NullChar}, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_TrimEnd">TrimEnd Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />