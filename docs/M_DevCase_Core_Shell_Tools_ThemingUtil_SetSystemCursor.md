# ThemingUtil.SetSystemCursor Method 
 

Sets the system cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetSystemCursor(
	string filePath,
	SystemCursorId cursorType
)
```

**VB**<br />
``` VB
Public Shared Sub SetSystemCursor ( 
	filePath As String,
	cursorType As SystemCursorId
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim cursorType As SystemCursorIdThemingUtil.SetSystemCursor(filePath, cursorType)
```

**C++**<br />
``` C++
public:
static void SetSystemCursor(
	String^ filePath, 
	SystemCursorId cursorType
)
```

**F#**<br />
``` F#
static member SetSystemCursor : 
        filePath : string * 
        cursorType : SystemCursorId -> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The cursor file path.</dd><dt>cursorType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SystemCursorId">DevCase.Interop.Unmanaged.Win32.Enums.SystemCursorId</a><br />The cursor type.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SetSystemCursor("C:\Windows\Cursors\aero_pen.cur", SystemCursorId.Arrow)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ThemingUtil">ThemingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />