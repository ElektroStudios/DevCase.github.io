# Converter.Started Event
 

Event raised when the `CoreConverter.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<CoreConverterStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of CoreConverterStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of CoreConverterStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<CoreConverterStartedEventArgs^>^ Started {
	void add (EventHandler<CoreConverterStartedEventArgs^>^ value);
	void remove (EventHandler<CoreConverterStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<CoreConverterStartedEventArgs>,
    CoreConverterStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterStartedEventArgs">CoreConverterStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />