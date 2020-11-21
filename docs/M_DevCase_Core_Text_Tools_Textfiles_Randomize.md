# Textfiles.Randomize Method (String, String, Encoding)
 

Randomizes the lines of the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Randomize(
	string sourceFilepath,
	string targetFilepath,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub Randomize ( 
	sourceFilepath As String,
	targetFilepath As String,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim enc As EncodingTextfiles.Randomize(sourceFilepath, targetFilepath, 
	enc)
```

**C++**<br />
``` C++
public:
static void Randomize(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Randomize : 
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
Randomize("C:\old file.txt", "C:\new file.txt", Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Randomize">Randomize Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />