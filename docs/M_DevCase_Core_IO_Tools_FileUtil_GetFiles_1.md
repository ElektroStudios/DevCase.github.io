# FileUtil.GetFiles Method (String, SearchOption, IEnumerable(String), IEnumerable(String), Boolean, Boolean)
 

Gets the files those matches the criteria inside the specified directory and/or sub-directories.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<FileInfo> GetFiles(
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
Public Shared Function GetFiles ( 
	dirPath As String,
	searchOption As SearchOption,
	Optional fileNamePatterns As IEnumerable(Of String) = Nothing,
	Optional fileExtPatterns As IEnumerable(Of String) = Nothing,
	Optional ignoreCase As Boolean = true,
	Optional throwOnError As Boolean = false
) As IEnumerable(Of FileInfo)
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim searchOption As SearchOption
Dim fileNamePatterns As IEnumerable(Of String)
Dim fileExtPatterns As IEnumerable(Of String)
Dim ignoreCase As Boolean
Dim throwOnError As Boolean
Dim returnValue As IEnumerable(Of FileInfo)

returnValue = FileUtil.GetFiles(dirPath, 
	searchOption, fileNamePatterns, 
	fileExtPatterns, ignoreCase, throwOnError)
```

**C++**<br />
``` C++
public:
static IEnumerable<FileInfo^>^ GetFiles(
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
static member GetFiles : 
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
-> IEnumerable<FileInfo> 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The root directory path to search for files.</dd><dt>searchOption</dt><dd>Type: System.IO.SearchOption<br />The searching mode.</dd><dt>fileNamePatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The file name pattern(s) to match.</dd><dt>fileExtPatterns (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The file extension pattern(s) to match.</dd><dt>ignoreCase (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), ignores the comparing case of *fileNamePatterns* and *fileExtPatterns* patterns.</dd><dt>throwOnError (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), exceptions will be thrown, like access denied to file or directory.</dd></dl>

#### Return Value
Type: IEnumerable(FileInfo)<br />An IEnumerable(T) instance containing the files information.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>dirPath or searchOption</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim files As List(Of FileInfo) =
    GetFiles("C:\Windows\System32", SearchOption.AllDirectories).ToList

Dim files As IEnumerable(Of FileInfo) =
    GetFiles(dirPath:="C:\Windows\System32",
             searchOption:=SearchOption.TopDirectoryOnly,
             fileNamePatterns:={"*"},
             fileExtPatterns:={"*.dll", "*.exe"},
             ignoreCase:=True,
             throwOnError:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetFiles">GetFiles Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />