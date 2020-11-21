# Textfiles.SortBy(*T*) Method (String, ListSortDirection, Func(String, *T*), Encoding)
 

Sorts the lines of the source textfile by evaluating the result of the given condition.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> SortBy<T>(
	string sourceFilepath,
	ListSortDirection sortDirection,
	Func<string, T> sortExpr,
	Encoding enc = null
)

```

**VB**<br />
``` VB
Public Shared Function SortBy(Of T) ( 
	sourceFilepath As String,
	sortDirection As ListSortDirection,
	sortExpr As Func(Of String, T),
	Optional enc As Encoding = Nothing
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim sourceFilepath As String
Dim sortDirection As ListSortDirection
Dim sortExpr As Func(Of String, T)
Dim enc As Encoding
Dim returnValue As IEnumerable(Of String)

returnValue = Textfiles.SortBy(sourceFilepath, 
	sortDirection, sortExpr, enc)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<String^>^ SortBy(
	String^ sourceFilepath, 
	ListSortDirection sortDirection, 
	Func<String^, T>^ sortExpr, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member SortBy : 
        sourceFilepath : string * 
        sortDirection : ListSortDirection * 
        sortExpr : Func<string, 'T> * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>sourceFilepath</dt><dd>Type: System.String<br />The source textfile path.</dd><dt>sortDirection</dt><dd>Type: System.ComponentModel.ListSortDirection<br />The sorting direction.</dd><dt>sortExpr</dt><dd>Type: System.Func(String, *T*)<br />The sorting expression to evaluate.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />The file encoding used to read the textfile.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Text.Tools.Textfiles.SortBy``1(System.String,System.ComponentModel.ListSortDirection,System.Func{System.String,``0},System.Text.Encoding)"\]</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) that contains the sorted lines.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>sortDirection</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lines As IEnumerable(Of String) = SortBy("C:\file.txt", ListSortDirection.Ascending, Function(line As String) line.EndsWith("5"), Encoding.Default)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_Textfiles">Textfiles Class</a><br /><a href="Overload_DevCase_Core_Text_Tools_Textfiles_SortBy">SortBy Overload</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />