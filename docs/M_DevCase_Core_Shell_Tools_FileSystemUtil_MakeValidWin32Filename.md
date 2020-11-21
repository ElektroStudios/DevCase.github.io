# FileSystemUtil.MakeValidWin32Filename Method 
 

Invokes an item verb on the specified file or directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string MakeValidWin32Filename(
	string filename,
	char replacementChar = '_'
)
```

**VB**<br />
``` VB
Public Shared Function MakeValidWin32Filename ( 
	filename As String,
	Optional replacementChar As Char = "_"C
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filename As String
Dim replacementChar As Char
Dim returnValue As String

returnValue = FileSystemUtil.MakeValidWin32Filename(filename, 
	replacementChar)
```

**C++**<br />
``` C++
public:
static String^ MakeValidWin32Filename(
	String^ filename, 
	wchar_t replacementChar = L'_'
)
```

**F#**<br />
``` F#
static member MakeValidWin32Filename : 
        filename : string * 
        ?replacementChar : char 
(* Defaults:
        let _replacementChar = defaultArg replacementChar '_'
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>filename</dt><dd>Type: System.String<br />The item path.</dd><dt>replacementChar (Optional)</dt><dd>Type: System.Char<br />The verb.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Shell.Tools.FileSystemUtil.MakeValidWin32Filename(System.String,System.Char)"\]

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileSystemUtil">FileSystemUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />