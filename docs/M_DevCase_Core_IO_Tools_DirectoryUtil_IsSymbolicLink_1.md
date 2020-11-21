# DirectoryUtil.IsSymbolicLink Method (String)
 

Determines whether whether the specified directory is a symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsSymbolicLink(
	string dirPath
)
```

**VB**<br />
``` VB
Public Shared Function IsSymbolicLink ( 
	dirPath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim dirPath As String
Dim returnValue As Boolean

returnValue = DirectoryUtil.IsSymbolicLink(dirPath)
```

**C++**<br />
``` C++
public:
static bool IsSymbolicLink(
	String^ dirPath
)
```

**F#**<br />
``` F#
static member IsSymbolicLink : 
        dirPath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>dirPath</dt><dd>Type: System.String<br />The full directory path.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified directory is a symbolic link; otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>DirectoryNotFoundException</td><td /></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DirectoryUtil">DirectoryUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DirectoryUtil_IsSymbolicLink">IsSymbolicLink Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />