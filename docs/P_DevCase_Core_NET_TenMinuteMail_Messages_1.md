# TenMinuteMail.Messages Property (String)
 

Gets the inbox message with the specified message id.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual MailMessage this[
	string id
] { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Messages ( 
	id As String
) As MailMessage
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim id As String
Dim value As MailMessage

value = instance.Messages(id)

```

**C++**<br />
``` C++
public:
virtual property MailMessage^ Messages[String^ id] {
	MailMessage^ get (String^ id);
}
```

**F#**<br />
``` F#
abstract Messages : MailMessage with get
override Messages : MailMessage with get
```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />The message id.</dd></dl>

#### Property Value
Type: MailMessage<br />The inbox message with the specified message id.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="Overload_DevCase_Core_NET_TenMinuteMail_Messages">Messages Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />