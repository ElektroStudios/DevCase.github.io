# VisualBasicProjectFileManager.ImportedNamespaces Property 
 

Gets or sets the imported namespaces.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SortedSet<string> ImportedNamespaces { get; set; }
```

**VB**<br />
``` VB
Public Property ImportedNamespaces As SortedSet(Of String)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As SortedSet(Of String)

value = instance.ImportedNamespaces

instance.ImportedNamespaces = value
```

**C++**<br />
``` C++
public:
property SortedSet<String^>^ ImportedNamespaces {
	SortedSet<String^>^ get ();
	void set (SortedSet<String^>^ value);
}
```

**F#**<br />
``` F#
member ImportedNamespaces : SortedSet<string> with get, set

```


#### Property Value
Type: SortedSet(String)<br />The imported namespaces.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vbproj As New VisualBasicProjectFileManager("C:\project.vbproj")
Dim importedNamespaces As SortedSet(Of String) = vbproj.ImportedNamespaces
importedNamespaces.Clear()
importedNamespaces.Add("System")
vbproj.ImportedNamespaces = importedNamespaces
vbproj.Document.Save("C:\modified.vbproj", SaveOptions.None)
Process.Start("notepad.exe", "C:\modified.vbproj")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />