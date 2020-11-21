# GraphicalUtil.LoadCursorFromFile Method (FileInfo)
 

Creates a Cursor based on a cursor file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Cursor LoadCursorFromFile(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function LoadCursorFromFile ( 
	file As FileInfo
) As Cursor
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As Cursor

returnValue = GraphicalUtil.LoadCursorFromFile(file)
```

**C++**<br />
``` C++
public:
static Cursor^ LoadCursorFromFile(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member LoadCursorFromFile : 
        file : FileInfo -> Cursor 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The cursor file.</dd></dl>

#### Return Value
Type: Cursor<br />The resulting Cursor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td /></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_LoadCursorFromFile">LoadCursorFromFile Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />