# TenMinuteMail.Messages Property 
 

Gets the inbox messages.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IEnumerable<MailMessage> Messages { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Messages As IEnumerable(Of MailMessage)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim value As IEnumerable(Of MailMessage)

value = instance.Messages

```

**C++**<br />
``` C++
public:
virtual property IEnumerable<MailMessage^>^ Messages {
	IEnumerable<MailMessage^>^ get ();
}
```

**F#**<br />
``` F#
abstract Messages : IEnumerable<MailMessage> with get
override Messages : IEnumerable<MailMessage> with get
```


#### Property Value
Type: IEnumerable(MailMessage)<br />The inbox messages.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="Overload_DevCase_Core_NET_TenMinuteMail_Messages">Messages Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />