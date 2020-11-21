# GraphicalUtil.LoadCursorFromFile Method (String)
 

Creates a Cursor based on a cursor file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Cursor LoadCursorFromFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function LoadCursorFromFile ( 
	filepath As String
) As Cursor
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Cursor

returnValue = GraphicalUtil.LoadCursorFromFile(filepath)
```

**C++**<br />
``` C++
public:
static Cursor^ LoadCursorFromFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member LoadCursorFromFile : 
        filepath : string -> Cursor 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The cursor filepath.</dd></dl>

#### Return Value
Type: Cursor<br />The resulting Cursor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td /></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_LoadCursorFromFile">LoadCursorFromFile Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />