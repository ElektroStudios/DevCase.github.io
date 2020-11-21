# VisualBasicProjectFileManager Constructor (FileInfo)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public VisualBasicProjectFileManager(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As FileInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo

Dim instance As New VisualBasicProjectFileManager(file)
```

**C++**<br />
``` C++
public:
VisualBasicProjectFileManager(
	FileInfo^ file
)
```

**F#**<br />
``` F#
new : 
        file : FileInfo -> VisualBasicProjectFileManager
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source .vbproj project file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>file;The specified file isn't a VisualBasic.NET project file.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="Overload_DevCase_Core_Application_Settings_VisualBasicProjectFileManager__ctor">VisualBasicProjectFileManager Overload</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />