# VisualBasicProjectFileManager.ReferencedAssemblies Property 
 

Gets or sets the referenced assemblies.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SortedDictionary<string, string> ReferencedAssemblies { get; set; }
```

**VB**<br />
``` VB
Public Property ReferencedAssemblies As SortedDictionary(Of String, String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As SortedDictionary(Of String, String)

value = instance.ReferencedAssemblies

instance.ReferencedAssemblies = value
```

**C++**<br />
``` C++
public:
property SortedDictionary<String^, String^>^ ReferencedAssemblies {
	SortedDictionary<String^, String^>^ get ();
	void set (SortedDictionary<String^, String^>^ value);
}
```

**F#**<br />
``` F#
member ReferencedAssemblies : SortedDictionary<string, string> with get, set

```


#### Property Value
Type: SortedDictionary(String, String)<br />The referenced assemblies.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
Dim referencedAssemblies As SortedDictionary(Of String, String) = vbproj.ReferencedAssemblies
referencedAssemblies.Clear()
referencedAssemblies.Add("System", "") ' Assemblies stored in GAC directory doesnt's require a hint path.
referencedAssemblies.Add("DevCase.Application", "..\..\DevCase\DevCase.Application.dll") ' Relative path.
referencedAssemblies.Add("DevCase.Core", "C:\DevCase\DevCase.Core.dll") ' Absolute path.
vbproj.ReferencedAssemblies = referencedAssemblies
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />