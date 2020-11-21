# UndoRedoItem.Event Property 
 

Gets or sets the control event that refers to the undo/redo data.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Event { get; set; }
```

**VB**<br />
``` VB
Public Property Event As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As UndoRedoItem
Dim value As Integer

value = instance.Event

instance.Event = value
```

**C++**<br />
``` C++
public:
property int Event {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member Event : int with get, set

```


#### Property Value
Type: Int32<br />The control event that refers to the undo/redo data.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_UndoRedoItem">UndoRedoItem Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />