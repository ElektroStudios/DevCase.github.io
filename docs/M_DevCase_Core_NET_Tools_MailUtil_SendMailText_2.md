# MailUtil.SendMailText Method (SmtpClient, NetworkCredential, String, String, MailAddress, Attachment[])
 

Sends a mail with a plain text body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SendMailText(
	SmtpClient smtpClient,
	NetworkCredential credential,
	string subject,
	string body,
	MailAddress address,
	params Attachment[] attachments
)
```

**VB**<br />
``` VB
Public Shared Sub SendMailText ( 
	smtpClient As SmtpClient,
	credential As NetworkCredential,
	subject As String,
	body As String,
	address As MailAddress,
	ParamArray attachments As Attachment()
)
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim credential As NetworkCredential
Dim subject As String
Dim body As String
Dim address As MailAddress
Dim attachments As Attachment()

MailUtil.SendMailText(smtpClient, credential, 
	subject, body, address, attachments)
```

**C++**<br />
``` C++
public:
static void SendMailText(
	SmtpClient^ smtpClient, 
	NetworkCredential^ credential, 
	String^ subject, 
	String^ body, 
	MailAddress^ address, 
	... array<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
static member SendMailText : 
        smtpClient : SmtpClient * 
        credential : NetworkCredential * 
        subject : string * 
        body : string * 
        address : MailAddress * 
        attachments : Attachment[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailText(System.Net.Mail.SmtpClient,System.Net.NetworkCredential,System.String,System.String,System.Net.Mail.MailAddress,System.Net.Mail.Attachment[])"\]</dd><dt>credential</dt><dd>Type: System.Net.NetworkCredential<br />The credential containing the username and password for the mail account.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.Net.Mail.MailAddress<br />The target address that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Net.Mail.Attachment[]<br />The file(s) to attach in this e-mail.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim credential As New NetworkCredential("Username@Hotmail.com", "Password")
SendMailText(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, credential, "Email Subject", "Message Body", New MailAddress("address@domain.com"), New Attachment("C:\File.txt"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailText">SendMailText Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />