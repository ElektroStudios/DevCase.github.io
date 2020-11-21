# GraphicalUtil.LoadCursorFromResource Method 
 

Creates a Cursor based on the data contained in a managed .NET resource.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Cursor LoadCursorFromResource(
	byte[] resource,
	bool deleteTempFile = false
)
```

**VB**<br />
``` VB
Public Shared Function LoadCursorFromResource ( 
	resource As Byte(),
	Optional deleteTempFile As Boolean = false
) As Cursor
```

**VB Usage**<br />
``` VB Usage
Dim resource As Byte()
Dim deleteTempFile As Boolean
Dim returnValue As Cursor

returnValue = GraphicalUtil.LoadCursorFromResource(resource, 
	deleteTempFile)
```

**C++**<br />
``` C++
public:
static Cursor^ LoadCursorFromResource(
	array<unsigned char>^ resource, 
	bool deleteTempFile = false
)
```

**F#**<br />
``` F#
static member LoadCursorFromResource : 
        resource : byte[] * 
        ?deleteTempFile : bool 
(* Defaults:
        let _deleteTempFile = defaultArg deleteTempFile false
*)
-> Cursor 

```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: System.Byte[]<br />The resource data (a cursor file).</dd><dt>deleteTempFile (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), delete the temp cursor file extracted from the .NET managed resource.</dd></dl>

#### Return Value
Type: Cursor<br />The resulting Cursor.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td /></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />