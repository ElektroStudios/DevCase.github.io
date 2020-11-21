# Textfiles.Sort Method (String, String, ListSortDirection, Encoding)
 

Sorts the lines of the source textfile, then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Sort(
	string sourceFilepath,
	string targetFilepath,
	ListSortDirection sortDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Sub Sort ( 
	sourceFilepath As String,
	targetFilepath As String,
	sortDirection As ListSortDirection,
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim sortDirection As ListSortDirection
Dim enc As EncodingTextfiles.Sort(sourceFilepath, targetFilepath, 
	sortDirection, enc)
```

**C++**<br />
``` C++
public:
static void Sort(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	ListSortDirection sortDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Sort : 
        sourceFilepath : string * 
        targetFilepath : string * 
        sortDirection : ListSortDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>sortDirection</dt><dd>Type: System.ComponentModel.ListSortDirection<br />The sorting direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Sort("C:\old file.txt", "C:\new file.txt", ListSortDirection.Ascending, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Sort">Sort Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />