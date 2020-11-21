# Converter.ProgressChanged Event
 

Event raised when `CoreConverter.exe` task progress has been changed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<CoreConverterProgressEventArgs> ProgressChanged
```

**VB**<br />
``` VB
Public Event ProgressChanged As EventHandler(Of CoreConverterProgressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of CoreConverterProgressEventArgs)

AddHandler instance.ProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<CoreConverterProgressEventArgs^>^ ProgressChanged {
	void add (EventHandler<CoreConverterProgressEventArgs^>^ value);
	void remove (EventHandler<CoreConverterProgressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ProgressChanged : IEvent<EventHandler<CoreConverterProgressEventArgs>,
    CoreConverterProgressEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs">CoreConverterProgressEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />