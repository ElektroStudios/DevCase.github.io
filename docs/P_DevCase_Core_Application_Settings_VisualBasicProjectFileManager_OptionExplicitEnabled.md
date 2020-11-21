# VisualBasicProjectFileManager.OptionExplicitEnabled Property 
 

Gets or sets a value that determines whether `OptionExplicit` is enabled by default in the project.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool OptionExplicitEnabled { get; set; }
```

**VB**<br />
``` VB
Public Property OptionExplicitEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As Boolean

value = instance.OptionExplicitEnabled

instance.OptionExplicitEnabled = value
```

**C++**<br />
``` C++
public:
property bool OptionExplicitEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member OptionExplicitEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) to enable `OptionExplicit`, otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
vbproj.OptionExplicitEnabled = True
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />