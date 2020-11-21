# Textfiles.Sort Method (String, ListSortDirection, Encoding)
 

Sorts the lines of the source textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> Sort(
	string sourceFilepath,
	ListSortDirection sortDirection,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function Sort ( 
	sourceFilepath As String,
	sortDirection As ListSortDirection,
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim sortDirection As ListSortDirection
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.Sort(sourceFilepath, 
	sortDirection, enc)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ Sort(
	String^ sourceFilepath, 
	ListSortDirection sortDirection, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member Sort : 
        sourceFilepath : string * 
        sortDirection : ListSortDirection * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>sortDirection</dt><dd>Type: System.ComponentModel.ListSortDirection<br />The sorting direction.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the sorted lines.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>sortDirection</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = Sort("C:\file.txt", ListSortDirection.Ascending, Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_Sort">Sort Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />