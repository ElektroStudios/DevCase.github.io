# VisualBasicProjectFileManager.TargetFrameworkVersion Property 
 

Gets or sets the target framework version.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TargetFrameworkVersion { get; set; }
```

**VB**<br />
``` VB
Public Property TargetFrameworkVersion As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As String

value = instance.TargetFrameworkVersion

instance.TargetFrameworkVersion = value
```

**C++**<br />
``` C++
public:
property String^ TargetFrameworkVersion {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member TargetFrameworkVersion : string with get, set

```


#### Property Value
Type: String<br />The target framework version.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.TargetFrameworkVersion = "4.5"
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />