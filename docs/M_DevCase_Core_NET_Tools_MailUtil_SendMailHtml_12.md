# MailUtil.SendMailHtml Method (SmtpClient, String, String, String, String, MailAddress)
 

Sends a mail with a HTML body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SendMailHtml(
	SmtpClient smtpClient,
	string username,
	string password,
	string subject,
	string body,
	MailAddress address
)
```

**VB**<br />
``` VB
Public Shared Sub SendMailHtml ( 
	smtpClient As SmtpClient,
	username As String,
	password As String,
	subject As String,
	body As String,
	address As MailAddress
)
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim username As String
Dim password As String
Dim subject As String
Dim body As String
Dim address As MailAddressMailUtil.SendMailHtml(smtpClient, username, 
	password, subject, body, address)
```

**C++**<br />
``` C++
public:
static void SendMailHtml(
	SmtpClient^ smtpClient, 
	String^ username, 
	String^ password, 
	String^ subject, 
	String^ body, 
	MailAddress^ address
)
```

**F#**<br />
``` F#
static member SendMailHtml : 
        smtpClient : SmtpClient * 
        username : string * 
        password : string * 
        subject : string * 
        body : string * 
        address : MailAddress -> unit 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailHtml(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.Net.Mail.MailAddress)"\]</dd><dt>username</dt><dd>Type: System.String<br />The mail account username.</dd><dt>password</dt><dd>Type: System.String<br />The mail account password.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.Net.Mail.MailAddress<br />The target address that will receive our sent mail.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SendMailHtml(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, "Username@Hotmail.com", "Password", "Email Subject", "Message Body", New MailAddress("address@domain.com"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailHtml">SendMailHtml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />