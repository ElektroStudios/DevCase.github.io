# TenMinuteMail.Reply Method (MailMessage, String)
 

Replies to the specified MailMessage.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Reply(
	MailMessage msg,
	string body
)
```

**VB**<br />
``` VB
Public Overridable Sub Reply ( 
	msg As MailMessage,
	body As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim msg As MailMessage
Dim body As String

instance.Reply(msg, body)
```

**C++**<br />
``` C++
public:
virtual void Reply(
	MailMessage^ msg, 
	String^ body
)
```

**F#**<br />
``` F#
abstract Reply : 
        msg : MailMessage * 
        body : string -> unit 
override Reply : 
        msg : MailMessage * 
        body : string -> unit 
```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: System.Net.Mail.MailMessage<br />The MailMessage.</dd><dt>body</dt><dd>Type: System.String<br />The body.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="Overload_DevCase_Core_NET_TenMinuteMail_Reply">Reply Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />