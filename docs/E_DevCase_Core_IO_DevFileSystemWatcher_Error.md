# DevFileSystemWatcher.Error Event
 

Occurs when this instance is unable to continue monitoring changes or when the internal buffer overflows.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
public event ErrorEventHandler Error
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
Public Event Error As ErrorEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevFileSystemWatcher
Dim handler As ErrorEventHandler

AddHandler instance.Error, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
 event ErrorEventHandler^ Error {
	void add (ErrorEventHandler^ value);
	void remove (ErrorEventHandler^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
member Error : IEvent<ErrorEventHandler,
    ErrorEventArgs>

```


#### Value
Type: System.IO.ErrorEventHandler

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DevFileSystemWatcher">DevFileSystemWatcher Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />