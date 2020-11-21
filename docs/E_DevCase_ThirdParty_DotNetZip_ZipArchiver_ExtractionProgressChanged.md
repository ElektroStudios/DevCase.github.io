# ZipArchiver.ExtractionProgressChanged Event
 

Occurs when the extraction progress has changed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ExtractProgressEventArgs> ExtractionProgressChanged
```

**VB**<br />
``` VB
Public Event ExtractionProgressChanged As EventHandler(Of ExtractProgressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipArchiver
Dim handler As EventHandler(Of ExtractProgressEventArgs)

AddHandler instance.ExtractionProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ExtractProgressEventArgs^>^ ExtractionProgressChanged {
	void add (EventHandler<ExtractProgressEventArgs^>^ value);
	void remove (EventHandler<ExtractProgressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ExtractionProgressChanged : IEvent<EventHandler<ExtractProgressEventArgs>,
    ExtractProgressEventArgs>

```


#### Value
Type: System.EventHandler(ExtractProgressEventArgs)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipArchiver">ZipArchiver Class</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />