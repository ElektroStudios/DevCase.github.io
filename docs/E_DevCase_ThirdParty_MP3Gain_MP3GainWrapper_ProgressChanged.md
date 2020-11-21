# MP3GainWrapper.ProgressChanged Event
 

Event raised when `MP3Gain.exe` progress changes.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MP3GainProgressChangedEventArgs> ProgressChanged
```

**VB**<br />
``` VB
Public Event ProgressChanged As EventHandler(Of MP3GainProgressChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim handler As EventHandler(Of MP3GainProgressChangedEventArgs)

AddHandler instance.ProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MP3GainProgressChangedEventArgs^>^ ProgressChanged {
	void add (EventHandler<MP3GainProgressChangedEventArgs^>^ value);
	void remove (EventHandler<MP3GainProgressChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ProgressChanged : IEvent<EventHandler<MP3GainProgressChangedEventArgs>,
    MP3GainProgressChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainProgressChangedEventArgs">MP3GainProgressChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />