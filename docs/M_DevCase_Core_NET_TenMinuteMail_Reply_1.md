# TenMinuteMail.Reply Method (String, String)
 

Replies to a MailMessage with the specified message id.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Reply(
	string msgId,
	string body
)
```

**VB**<br />
``` VB
Public Overridable Sub Reply ( 
	msgId As String,
	body As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
Dim msgId As String
Dim body As String

instance.Reply(msgId, body)
```

**C++**<br />
``` C++
public:
virtual void Reply(
	String^ msgId, 
	String^ body
)
```

**F#**<br />
``` F#
abstract Reply : 
        msgId : string * 
        body : string -> unit 
override Reply : 
        msgId : string * 
        body : string -> unit 
```


#### Parameters
&nbsp;<dl><dt>msgId</dt><dd>Type: System.String<br />The message id of the MailMessage.</dd><dt>body</dt><dd>Type: System.String<br />The body.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail Class</a><br /><a href="Overload_DevCase_Core_NET_TenMinuteMail_Reply">Reply Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />