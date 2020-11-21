# ControlDragger.Controls Property 
 

Gets an IEnumerable(T) collection that contains the owner controls that can perform draggable operations.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public ReadOnlyCollection<ControlDragInfo> Controls { get; }
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public ReadOnly Property Controls As ReadOnlyCollection(Of ControlDragInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlDragger
Dim value As ReadOnlyCollection(Of ControlDragInfo)

value = instance.Controls

```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property ReadOnlyCollection<ControlDragInfo^>^ Controls {
	ReadOnlyCollection<ControlDragInfo^>^ get ();
}
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Controls : ReadOnlyCollection<ControlDragInfo> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a>)<br />The IEnumerable(T).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />