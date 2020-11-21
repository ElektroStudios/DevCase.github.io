# Textfiles.Reverse Method (String, String, Encoding)
 

Reverses the lines of the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Reverse(
	string sourceFilepath,
	string targetFilepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub Reverse ( 
	sourceFilepath As String,
	targetFilepath As String,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim enc As EncodingTextfiles.Reverse(sourceFilepath, targetFilepath, 
	enc)
```

**C++**<br />
``` C++
public:
static void Reverse(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Reverse : 
        sourceFilepath : string * 
        targetFilepath : string * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Reverse("C:\old file.txt", "C:\new file.txt", Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Reverse">Reverse Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />