# DevFileSystemWatcher.PathUnavailable Event
 

Occurs when the path specified in <a href="P_DevCase_Core_IO_DevFileSystemWatcher_Path">Path</a> property becomes unavailable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler PathUnavailable
```

**VB**<br />
``` VB
Public Event PathUnavailable As EventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevFileSystemWatcher
Dim handler As EventHandler

AddHandler instance.PathUnavailable, handler

```

**C++**<br />
``` C++
public:
 event EventHandler^ PathUnavailable {
	void add (EventHandler^ value);
	void remove (EventHandler^ value);
}
```

**F#**<br />
``` F#
member PathUnavailable : IEvent<EventHandler,
    EventArgs>

```


#### Value
Type: System.EventHandler

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DevFileSystemWatcher">DevFileSystemWatcher Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />