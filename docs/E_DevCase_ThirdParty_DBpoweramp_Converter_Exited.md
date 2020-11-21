# Converter.Exited Event
 

Event raised when the `CoreConverter.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<CoreConverterExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of CoreConverterExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of CoreConverterExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<CoreConverterExitedEventArgs^>^ Exited {
	void add (EventHandler<CoreConverterExitedEventArgs^>^ value);
	void remove (EventHandler<CoreConverterExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<CoreConverterExitedEventArgs>,
    CoreConverterExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterExitedEventArgs">CoreConverterExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />