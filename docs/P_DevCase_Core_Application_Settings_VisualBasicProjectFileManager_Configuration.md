# VisualBasicProjectFileManager.Configuration Property 
 

Gets or sets the project's configuration mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Configuration { get; set; }
```

**VB**<br />
``` VB
Public Property Configuration As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As String

value = instance.Configuration

instance.Configuration = value
```

**C++**<br />
``` C++
public:
property String^ Configuration {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Configuration : string with get, set

```


#### Property Value
Type: String<br />The project's configuration mode.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.Configuration = "Debug" ' Or "Release"
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />