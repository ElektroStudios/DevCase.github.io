# VisualBasicProjectFileManager.ProjectGuid Property 
 

Gets or sets the project GUID.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Guid ProjectGuid { get; set; }
```

**VB**<br />
``` VB
Public Property ProjectGuid As Guid
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As Guid

value = instance.ProjectGuid

instance.ProjectGuid = value
```

**C++**<br />
``` C++
public:
property Guid ProjectGuid {
	Guid get ();
	void set (Guid value);
}
```

**F#**<br />
``` F#
member ProjectGuid : Guid with get, set

```


#### Property Value
Type: Guid<br />The project GUID.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.ProjectGuid = New Guid("C370C005-08CA-4DD2-9902-4AB984F49818"}
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />