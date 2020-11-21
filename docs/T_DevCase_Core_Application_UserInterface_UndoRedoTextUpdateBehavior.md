# UndoRedoTextUpdateBehavior Enumeration
 

Specifies a Undo/Redo text-update behavior for an edit-control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum UndoRedoTextUpdateBehavior
```

**VB**<br />
``` VB
Public Enumeration UndoRedoTextUpdateBehavior
```

**VB Usage**<br />
``` VB Usage
Dim instance As UndoRedoTextUpdateBehavior
```

**C++**<br />
``` C++
public enum class UndoRedoTextUpdateBehavior
```

**F#**<br />
``` F#
type UndoRedoTextUpdateBehavior
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Application.UserInterface.UndoRedoTextUpdateBehavior.OnTextChanged">**OnTextChanged**</td><td>1</td><td>Updates the text for undo/redo every time that the text changes, for example, when a single character is added or removed.</td></tr><tr><td /><td target="F:DevCase.Core.Application.UserInterface.UndoRedoTextUpdateBehavior.OnLeave">**OnLeave**</td><td>2</td><td>Updates the text for undo/redo only when leaving the control focus.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />