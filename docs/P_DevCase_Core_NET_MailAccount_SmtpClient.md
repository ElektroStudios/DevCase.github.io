# MailAccount.SmtpClient Property 
 

Gets or sets the SmtpClient object that allows applications to send e-mails.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SmtpClient SmtpClient { get; set; }
```

**VB**<br />
``` VB
Public Property SmtpClient As SmtpClient
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MailAccount
Dim value As SmtpClient

value = instance.SmtpClient

instance.SmtpClient = value
```

**C++**<br />
``` C++
public:
property SmtpClient^ SmtpClient {
	SmtpClient^ get ();
	void set (SmtpClient^ value);
}
```

**F#**<br />
``` F#
member SmtpClient : SmtpClient with get, set

```


#### Property Value
Type: SmtpClient<br />The SmtpClient object that allows applications to send e-mails.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_MailAccount">MailAccount Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />