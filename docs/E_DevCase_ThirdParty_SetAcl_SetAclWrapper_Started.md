# SetAclWrapper.Started Event
 

Event raised when the `SetACL.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<SetAclStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of SetAclStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetAclWrapper
Dim handler As EventHandler(Of SetAclStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<SetAclStartedEventArgs^>^ Started {
	void add (EventHandler<SetAclStartedEventArgs^>^ value);
	void remove (EventHandler<SetAclStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<SetAclStartedEventArgs>,
    SetAclStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclStartedEventArgs">SetAclStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SetAcl_SetAclWrapper">SetAclWrapper Class</a><br /><a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl Namespace</a><br />