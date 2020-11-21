# FormDragger.Forms Property 
 

Gets an IEnumerable(T) collection that contains the owner Forms that can perform draggable operations.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public ReadOnlyCollection<FormDragInfo> Forms { get; }
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public ReadOnly Property Forms As ReadOnlyCollection(Of FormDragInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim value As ReadOnlyCollection(Of FormDragInfo)

value = instance.Forms

```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property ReadOnlyCollection<FormDragInfo^>^ Forms {
	ReadOnlyCollection<FormDragInfo^>^ get ();
}
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Forms : ReadOnlyCollection<FormDragInfo> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a>)<br />The IEnumerable(T).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />