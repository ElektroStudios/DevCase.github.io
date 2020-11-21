# Archiver.ExtractionProgressChanged Event
 

Occurs when the extraction progress has changed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ProgressEventArgs> ExtractionProgressChanged
```

**VB**<br />
``` VB
Public Event ExtractionProgressChanged As EventHandler(Of ProgressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Archiver
Dim handler As EventHandler(Of ProgressEventArgs)

AddHandler instance.ExtractionProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ProgressEventArgs^>^ ExtractionProgressChanged {
	void add (EventHandler<ProgressEventArgs^>^ value);
	void remove (EventHandler<ProgressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ExtractionProgressChanged : IEvent<EventHandler<ProgressEventArgs>,
    ProgressEventArgs>

```


#### Value
Type: System.EventHandler(ProgressEventArgs)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SevenZipSharp_Archiver">Archiver Class</a><br /><a href="N_DevCase_ThirdParty_SevenZipSharp">DevCase.ThirdParty.SevenZipSharp Namespace</a><br />