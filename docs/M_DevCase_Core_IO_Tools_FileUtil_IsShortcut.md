# FileUtil.IsShortcut Method 
 

Determines whether the specified file is a shortcut file (`.lnk`).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsShortcut(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function IsShortcut ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = FileUtil.IsShortcut(filepath)
```

**C++**<br />
``` C++
public:
static bool IsShortcut(
	String^ filepath
)
```

**F#**<br />
``` F#
static member IsShortcut : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the file is a shortcut; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />