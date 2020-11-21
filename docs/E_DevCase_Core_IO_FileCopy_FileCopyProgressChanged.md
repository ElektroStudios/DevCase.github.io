# FileCopy.FileCopyProgressChanged Event
 

Occurs when the progress of a file-copy operation has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<FileCopyProgressChangedEventArgs> FileCopyProgressChanged
```

**VB**<br />
``` VB
Public Event FileCopyProgressChanged As EventHandler(Of FileCopyProgressChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileCopy
Dim handler As EventHandler(Of FileCopyProgressChangedEventArgs)

AddHandler instance.FileCopyProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<FileCopyProgressChangedEventArgs^>^ FileCopyProgressChanged {
	void add (EventHandler<FileCopyProgressChangedEventArgs^>^ value);
	void remove (EventHandler<FileCopyProgressChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member FileCopyProgressChanged : IEvent<EventHandler<FileCopyProgressChangedEventArgs>,
    FileCopyProgressChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_FileCopyProgressChangedEventArgs">FileCopyProgressChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileCopy">FileCopy Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />