# SmtpClients.GoogleMailSmtpClient Property 
 

Gets a value that represents the SMTP client which allows applications to send e-mails through Google Gmail SMTP server. 

 Login webpage: <a href="https://accounts.google.com/servicelogin/" target="_blank">https://accounts.google.com/servicelogin/</a>

 Note that in order to send SMTP e-mails, you must enable application access for your GMail account by following the next url: 

<a href="http://www.google.com/settings/security/lesssecureapps" target="_blank">http://www.google.com/settings/security/lesssecureapps</a>

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SmtpClient GoogleMailSmtpClient { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property GoogleMailSmtpClient As SmtpClient
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As SmtpClient

value = SmtpClients.GoogleMailSmtpClient

```

**C++**<br />
``` C++
public:
static property SmtpClient^ GoogleMailSmtpClient {
	SmtpClient^ get ();
}
```

**F#**<br />
``` F#
static member GoogleMailSmtpClient : SmtpClient with get

```


#### Property Value
Type: SmtpClient<br />\[Missing <value> documentation for "P:DevCase.Core.NET.SmtpClients.GoogleMailSmtpClient"\]

## Remarks
Note that in order to send SMTP e-mails, you must enable application access for your GMail account by following the next url: 

<a href="http://www.google.com/settings/security/lesssecureapps" target="_blank">http://www.google.com/settings/security/lesssecureapps</a>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_SmtpClients">SmtpClients Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />