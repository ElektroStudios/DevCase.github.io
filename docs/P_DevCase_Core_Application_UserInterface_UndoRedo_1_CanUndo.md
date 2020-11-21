# UndoRedo(*T*).CanUndo Property 
 

Gets a value indicating whether this instance can perform a undo operation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool CanUndo { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CanUndo As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As UndoRedo
Dim value As Boolean

value = instance.CanUndo

```

**C++**<br />
``` C++
public:
property bool CanUndo {
	bool get ();
}
```

**F#**<br />
``` F#
member CanUndo : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if can undo; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_UndoRedo_1">UndoRedo(T) Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />