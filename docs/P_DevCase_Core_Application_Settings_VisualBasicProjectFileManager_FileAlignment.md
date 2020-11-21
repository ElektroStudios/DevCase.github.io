# VisualBasicProjectFileManager.FileAlignment Property 
 

Gets or sets the project's file alignment.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int FileAlignment { get; set; }
```

**VB**<br />
``` VB
Public Property FileAlignment As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As Integer

value = instance.FileAlignment

instance.FileAlignment = value
```

**C++**<br />
``` C++
public:
property int FileAlignment {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member FileAlignment : int with get, set

```


#### Property Value
Type: Int32<br />The project's file alignment.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.FileAlignment = 512
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />