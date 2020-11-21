# FileUtil.GetFilePaths Method (String, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)
 

Gets the filepaths those matches the criteria inside the specified directory and/or sub-directories.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<string> GetFilePaths(
	string dirPath,
	SearchOption searchOption,
	IEnumerable<string> fileNamePatterns = null,
	IEnumerable<string> fileExtPatterns = null,
	bool ignoreCase = true,
	bool throwOnError = false
)
```

**VB**<br />
``` VB
Public Shared Function GetFilePaths ( 
	dirPath As String,
	searchOption As SearchOption,
	Optional fileNamePatterns As IEnumerable(Of String) = Nothing,
	Optional fileExtPatterns As IEnumerable(Of String) = Nothing,
	Optional ignoreCase As Boolean = true,
	Optional throwOnError As Boolean = false
) As IEnumerable(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim searchOption As SearchOption
Dim fileNamePatterns As IEnumerable(Of String)
Dim fileExtPatterns As IEnumerable(Of String)
Dim ignoreCase As Boolean
Dim throwOnError As Boolean
Dim returnValue As IEnumerable(Of String)

returnValue = FileUtil.GetFilePaths(dirPath, 
	searchOption, fileNamePatterns, 
	fileExtPatterns, ignoreCase, throwOnError)
```

**C++**<br />
``` C++
public:
static IEnumerable<String^>^ GetFilePaths(
	String^ dirPath, 
	SearchOption searchOption, 
	IEnumerable<String^>^ fileNamePatterns = nullptr, 
	IEnumerable<String^>^ fileExtPatterns = nullptr, 
	bool ignoreCase = true, 
	bool throwOnError = false
)
```

**F#**<br />
``` F#
static member GetFilePaths : 
        dirPath : string * 
        searchOption : SearchOption * 
        ?fileNamePatterns : IEnumerable<string> * 
        ?fileExtPatterns : IEnumerable<string> * 
        ?ignoreCase : bool * 
        ?throwOnError : bool 
(* Defaults:
        let _fileNamePatterns = defaultArg fileNamePatterns null
        let _fileExtPatterns = defaultArg fileExtPatterns null
        let _ignoreCase = defaultArg ignoreCase true
        let _throwOnError = defaultArg throwOnError false
*)
-> IEnumerable<string> 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The root directory path to search for files.</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The searching mode.</dd><dt>fileNamePatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The file name pattern(s) to match.</dd><dt>fileExtPatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The file extension pattern(s) to match.</dd><dt>ignoreCase (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), ignores the comparing case of *fileNamePatterns* and *fileExtPatterns* patterns.</dd><dt>throwOnError (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), exceptions will be thrown, like access denied to file or directory.</dd></dl>

#### Return Value
Type: IEnumerable(String)<br />An IEnumerable(T) instance containing the filepaths.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>dirPath or searchOption</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim filePaths As List(Of String) =
    GetFilePaths("C:\Windows\System32", SearchOption.AllDirectories).ToList
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetFilePaths">GetFilePaths Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />