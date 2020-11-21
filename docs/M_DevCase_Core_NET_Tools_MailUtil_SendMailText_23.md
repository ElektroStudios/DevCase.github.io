# MailUtil.SendMailText Method (SmtpClient, String, String, String, String, String[], Attachment[])
 

Sends a mail with a plain text body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SendMailText(
	SmtpClient smtpClient,
	string username,
	string password,
	string subject,
	string body,
	string[] addresses,
	params Attachment[] attachments
)
```

**VB**<br />
``` VB
Public Shared Sub SendMailText ( 
	smtpClient As SmtpClient,
	username As String,
	password As String,
	subject As String,
	body As String,
	addresses As String(),
	ParamArray attachments As Attachment()
)
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim username As String
Dim password As String
Dim subject As String
Dim body As String
Dim addresses As String()
Dim attachments As Attachment()

MailUtil.SendMailText(smtpClient, username, 
	password, subject, body, addresses, 
	attachments)
```

**C++**<br />
``` C++
public:
static void SendMailText(
	SmtpClient^ smtpClient, 
	String^ username, 
	String^ password, 
	String^ subject, 
	String^ body, 
	array<String^>^ addresses, 
	... array<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
static member SendMailText : 
        smtpClient : SmtpClient * 
        username : string * 
        password : string * 
        subject : string * 
        body : string * 
        addresses : string[] * 
        attachments : Attachment[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailText(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.String[],System.Net.Mail.Attachment[])"\]</dd><dt>username</dt><dd>Type: System.String<br />The mail account username.</dd><dt>password</dt><dd>Type: System.String<br />The mail account password.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.String[]<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Net.Mail.Attachment[]<br />The file(s) to attach in this e-mail.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
SendMailText(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, "Username@Hotmail.com", "Password", "Email Subject", "Message Body", {"address1@domain.com", "address2@domain.com"}, New Attachment("C:\File.txt"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailText">SendMailText Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />