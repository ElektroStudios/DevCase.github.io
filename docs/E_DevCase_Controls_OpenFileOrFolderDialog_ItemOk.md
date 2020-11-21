# OpenFileOrFolderDialog.ItemOk Event
 

Occurs when the user clicks on the Open button on the dialog box to select a file or folder.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event CancelEventHandler ItemOk
```

**VB**<br />
``` VB
Public Event ItemOk As CancelEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenFileOrFolderDialog
Dim handler As CancelEventHandler

AddHandler instance.ItemOk, handler

```

**C++**<br />
``` C++
public:
 event CancelEventHandler^ ItemOk {
	void add (CancelEventHandler^ value);
	void remove (CancelEventHandler^ value);
}
```

**F#**<br />
``` F#
member ItemOk : IEvent<CancelEventHandler,
    CancelEventArgs>

```


#### Value
Type: System.ComponentModel.CancelEventHandler

## See Also


#### Reference
<a href="T_DevCase_Controls_OpenFileOrFolderDialog">OpenFileOrFolderDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />