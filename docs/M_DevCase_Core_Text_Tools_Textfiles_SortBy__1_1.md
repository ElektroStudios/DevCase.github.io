# Textfiles.SortBy(*T*) Method (String, String, ListSortDirection, Func(String, *T*), Encoding)
 

Sorts the lines of the source textfile by evaluating the result of the given condition. then writes the result in the target textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SortBy<T>(
	string sourceFilepath,
	string targetFilepath,
	ListSortDirection sortDirection,
	Func<string, T> sortExpr,
	Encoding enc = null
)

```

**VB**<br />
``` VB
Public Shared Sub SortBy(Of T) ( 
	sourceFilepath As String,
	targetFilepath As String,
	sortDirection As ListSortDirection,
	sortExpr As Func(Of String, T),
	Optional enc As Encoding = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim targetFilepath As String
Dim sortDirection As ListSortDirection
Dim sortExpr As Func(Of String, T)
Dim enc As EncodingTextfiles.SortBy(sourceFilepath, targetFilepath, 
	sortDirection, sortExpr, enc)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void SortBy(
	String^ sourceFilepath, 
	String^ targetFilepath, 
	ListSortDirection sortDirection, 
	Func<String^, T>^ sortExpr, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member SortBy : 
        sourceFilepath : string * 
        targetFilepath : string * 
        sortDirection : ListSortDirection * 
        sortExpr : Func<string, 'T> * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target textfile path.</dd><dt>sortDirection</dt><dd>Type: System.ComponentModel.ListSortDirection<br />The sorting direction.</dd><dt>sortExpr</dt><dd>Type: System.Func(String, *T*)<br />The sorting expression to evaluate.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read/write the textfile.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Text.Tools.Textfiles.SortBy``1(System.String,System.String,System.ComponentModel.ListSortDirection,System.Func{System.String,``0},System.Text.Encoding)"\]</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SortBy("C:\old file.txt", "C:\new file.txt", ListSortDirection.Ascending, Function(line As String) line.EndsWith("5"), Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_SortBy">SortBy Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />