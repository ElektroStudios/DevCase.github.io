# SetAclWrapper.Exited Event
 

Event raised when the `SetACL.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<SetAclExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of SetAclExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetAclWrapper
Dim handler As EventHandler(Of SetAclExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<SetAclExitedEventArgs^>^ Exited {
	void add (EventHandler<SetAclExitedEventArgs^>^ value);
	void remove (EventHandler<SetAclExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<SetAclExitedEventArgs>,
    SetAclExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclExitedEventArgs">SetAclExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SetAcl_SetAclWrapper">SetAclWrapper Class</a><br /><a href="N_DevCase_ThirdParty_SetAcl">DevCase.ThirdParty.SetAcl Namespace</a><br />