# TenMinuteMail.MailMessageArrived Event
 

Occurs when a new inbox message arrived.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MailMessageArrivedEventArgs> MailMessageArrived
```

**VB**<br />
``` VB
Public Event MailMessageArrived As EventHandler(Of MailMessageArrivedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim handler As EventHandler(Of MailMessageArrivedEventArgs)

AddHandler instance.MailMessageArrived, handler

```

**C++**<br />
``` C++
public:
virtual  event EventHandler<MailMessageArrivedEventArgs^>^ MailMessageArrived {
	void add (EventHandler<MailMessageArrivedEventArgs^>^ value);
	void remove (EventHandler<MailMessageArrivedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
abstract MailMessageArrived : IEvent<EventHandler<MailMessageArrivedEventArgs>,
    MailMessageArrivedEventArgs>
override MailMessageArrived : IEvent<EventHandler<MailMessageArrivedEventArgs>,
    MailMessageArrivedEventArgs>
```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_NET_Eventing_MailMessageArrivedEventArgs">MailMessageArrivedEventArgs</a>)

#### Implements
<a href="E_DevCase_Core_NET_IDisposableMail_MailMessageArrived">IDisposableMail.MailMessageArrived</a><br />

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />