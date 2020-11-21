# VisualBasicProjectFileManager.ItemGroupNodes Property 
 

Gets a collection of the `<ItemGroup>` nodes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IEnumerable<XElement> ItemGroupNodes { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property ItemGroupNodes As IEnumerable(Of XElement)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As VisualBasicProjectFileManager
Dim value As IEnumerable(Of XElement)

value = instance.ItemGroupNodes

```

**C++**<br />
``` C++
public:
property IEnumerable<XElement^>^ ItemGroupNodes {
	IEnumerable<XElement^>^ get ();
}
```

**F#**<br />
``` F#
member ItemGroupNodes : IEnumerable<XElement> with get

```


#### Property Value
Type: IEnumerable(XElement)<br />A collection of the `<ItemGroup>` nodes.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Settings_VisualBasicProjectFileManager">VisualBasicProjectFileManager Class</a><br /><a href="N_DevCase_Core_Application_Settings">DevCase.Core.Application.Settings Namespace</a><br />