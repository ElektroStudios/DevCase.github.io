# FileSplitter.ProgressChanged Event
 

Occurs when the progress changes when splitting or merging a file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<FileSplitterProgressChangedEventArgs> ProgressChanged
```

**VB**<br />
``` VB
Public Event ProgressChanged As EventHandler(Of FileSplitterProgressChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileSplitter
Dim handler As EventHandler(Of FileSplitterProgressChangedEventArgs)

AddHandler instance.ProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<FileSplitterProgressChangedEventArgs^>^ ProgressChanged {
	void add (EventHandler<FileSplitterProgressChangedEventArgs^>^ value);
	void remove (EventHandler<FileSplitterProgressChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ProgressChanged : IEvent<EventHandler<FileSplitterProgressChangedEventArgs>,
    FileSplitterProgressChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_FileSplitterProgressChangedEventArgs">FileSplitterProgressChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileSplitter">FileSplitter Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />