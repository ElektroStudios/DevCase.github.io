# FileUtil.GetSymbolicLinkTarget Method (String)
 

Gets the target of the specified symbolic link.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetSymbolicLinkTarget(
	string filePath
)
```

**VB**<br />
``` VB
Public Shared Function GetSymbolicLinkTarget ( 
	filePath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim returnValue As String

returnValue = FileUtil.GetSymbolicLinkTarget(filePath)
```

**C++**<br />
``` C++
public:
static String^ GetSymbolicLinkTarget(
	String^ filePath
)
```

**F#**<br />
``` F#
static member GetSymbolicLinkTarget : 
        filePath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The full path of a symbolic link that points to a file.</dd></dl>

#### Return Value
Type: String<br />The target of the specified symbolic link.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FileNotFoundException</td><td /></tr><tr><td>ArgumentException</td><td>The specified file is not a symbolic link. - filePath</td></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_FileUtil_GetSymbolicLinkTarget">GetSymbolicLinkTarget Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />