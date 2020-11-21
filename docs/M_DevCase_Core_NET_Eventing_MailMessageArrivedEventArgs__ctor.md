# MailMessageArrivedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_Eventing_MailMessageArrivedEventArgs">MailMessageArrivedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MailMessageArrivedEventArgs(
	MailMessage msg
)
```

**VB**<br />
``` VB
Public Sub New ( 
	msg As MailMessage
)
```

**VB Usage**<br />
``` VB Usage
Dim msg As MailMessage

Dim instance As New MailMessageArrivedEventArgs(msg)
```

**C++**<br />
``` C++
public:
MailMessageArrivedEventArgs(
	MailMessage^ msg
)
```

**F#**<br />
``` F#
new : 
        msg : MailMessage -> MailMessageArrivedEventArgs
```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: System.Net.Mail.MailMessage<br />The mail message that arrived.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Eventing_MailMessageArrivedEventArgs">MailMessageArrivedEventArgs Class</a><br /><a href="N_DevCase_Core_NET_Eventing">DevCase.Core.NET.Eventing Namespace</a><br />