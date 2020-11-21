# ZipArchiver.CompressionProgressChanged Event
 

Occurs when the compression progress has changed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<SaveProgressEventArgs> CompressionProgressChanged
```

**VB**<br />
``` VB
Public Event CompressionProgressChanged As EventHandler(Of SaveProgressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim handler As EventHandler(Of SaveProgressEventArgs)

AddHandler instance.CompressionProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<SaveProgressEventArgs^>^ CompressionProgressChanged {
	void add (EventHandler<SaveProgressEventArgs^>^ value);
	void remove (EventHandler<SaveProgressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member CompressionProgressChanged : IEvent<EventHandler<SaveProgressEventArgs>,
    SaveProgressEventArgs>

```


#### Value
Type: System.EventHandler(SaveProgressEventArgs)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />