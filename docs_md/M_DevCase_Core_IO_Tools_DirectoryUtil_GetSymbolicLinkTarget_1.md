# DirectoryUtil.GetSymbolicLinkTarget Method (String)
 

Gets the target of the specified symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetSymbolicLinkTarget(
	string dirPath
)
```

**VB**<br />
``` VB
Public Shared Function GetSymbolicLinkTarget ( 
	dirPath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim returnValue As String

returnValue = DirectoryUtil.GetSymbolicLinkTarget(dirPath)
```

**C++**<br />
``` C++
public:
static String^ GetSymbolicLinkTarget(
	String^ dirPath
)
```

**F#**<br />
``` F#
static member GetSymbolicLinkTarget : 
        dirPath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The full path of a symbolic link that points to a directory.</dd></dl>

#### Return Value
Type: String<br />The target of the specified symbolic link.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>DirectoryNotFoundException</td><td /></tr><tr><td>ArgumentException</td><td>The specified directory is not a symbolic link. - dirPath</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_GetSymbolicLinkTarget">GetSymbolicLinkTarget Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />