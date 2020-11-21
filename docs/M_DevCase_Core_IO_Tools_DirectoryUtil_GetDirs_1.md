# DirectoryUtil.GetDirs Method (String, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)
 

Gets the directories those matches the criteria inside the specified directory and/or sub-DirectoryUtil.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<DirectoryInfo> GetDirs(
	string dirPath,
	SearchOption searchOption,
	IEnumerable<string> dirPathPatterns = null,
	IEnumerable<string> dirNamePatterns = null,
	bool ignoreCase = true,
	bool throwOnError = false
)
```

**VB**<br />
``` VB
Public Shared Function GetDirs ( 
	dirPath As String,
	searchOption As SearchOption,
	Optional dirPathPatterns As IEnumerable(Of String) = Nothing,
	Optional dirNamePatterns As IEnumerable(Of String) = Nothing,
	Optional ignoreCase As Boolean = true,
	Optional throwOnError As Boolean = false
) As IEnumerable(Of DirectoryInfo)
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim searchOption As SearchOption
Dim dirPathPatterns As IEnumerable(Of String)
Dim dirNamePatterns As IEnumerable(Of String)
Dim ignoreCase As Boolean
Dim throwOnError As Boolean
Dim returnValue As IEnumerable(Of DirectoryInfo)

returnValue = DirectoryUtil.GetDirs(dirPath, 
	searchOption, dirPathPatterns, dirNamePatterns, 
	ignoreCase, throwOnError)
```

**C++**<br />
``` C++
public:
static IEnumerable<DirectoryInfo^>^ GetDirs(
	String^ dirPath, 
	SearchOption searchOption, 
	IEnumerable<String^>^ dirPathPatterns = nullptr, 
	IEnumerable<String^>^ dirNamePatterns = nullptr, 
	bool ignoreCase = true, 
	bool throwOnError = false
)
```

**F#**<br />
``` F#
static member GetDirs : 
        dirPath : string * 
        searchOption : SearchOption * 
        ?dirPathPatterns : IEnumerable<string> * 
        ?dirNamePatterns : IEnumerable<string> * 
        ?ignoreCase : bool * 
        ?throwOnError : bool 
(* Defaults:
        let _dirPathPatterns = defaultArg dirPathPatterns null
        let _dirNamePatterns = defaultArg dirNamePatterns null
        let _ignoreCase = defaultArg ignoreCase true
        let _throwOnError = defaultArg throwOnError false
*)
-> IEnumerable<DirectoryInfo> 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The root directory path to search for DirectoryUtil.</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The searching mode.</dd><dt>dirPathPatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The directory path pattern(s) to match.</dd><dt>dirNamePatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The directory name pattern(s) to match.</dd><dt>ignoreCase (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), ignores the comparing case of *dirPathPatterns* and *dirNamePatterns* patterns.</dd><dt>throwOnError (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), exceptions will be thrown, like access denied to directory.</dd></dl>

#### Return Value
Type: IEnumerable(DirectoryInfo)<br />An IEnumerable(T) instance containing the dirrectories information.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>dirPath or searchOption</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dirs As List(Of DirectoryInfo) =
    GetDirs("C:\Windows\System32", SearchOption.AllDirectories).ToList

Dim dirs As IEnumerable(Of DirectoryInfo) =
    GetDirs(dirPath:="C:\Windows\System32",
            searchOption:=SearchOption.TopDirectoryOnly,
            dirPathPatterns:={"*"},
            dirNamePatterns:={"*Microsoft*"},
            ignoreCase:=True,
            throwOnError:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_GetDirs">GetDirs Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />