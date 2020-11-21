# MailUtil.SendMailHtml Method (SmtpClient, NetworkCredential, String, String, String[], Attachment[])
 

Sends a mail with a HTML body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SendMailHtml(
	SmtpClient smtpClient,
	NetworkCredential credential,
	string subject,
	string body,
	string[] addresses,
	params Attachment[] attachments
)
```

**VB**<br />
``` VB
Public Shared Sub SendMailHtml ( 
	smtpClient As SmtpClient,
	credential As NetworkCredential,
	subject As String,
	body As String,
	addresses As String(),
	ParamArray attachments As Attachment()
)
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim credential As NetworkCredential
Dim subject As String
Dim body As String
Dim addresses As String()
Dim attachments As Attachment()

MailUtil.SendMailHtml(smtpClient, credential, 
	subject, body, addresses, attachments)
```

**C++**<br />
``` C++
public:
static void SendMailHtml(
	SmtpClient^ smtpClient, 
	NetworkCredential^ credential, 
	String^ subject, 
	String^ body, 
	array<String^>^ addresses, 
	... array<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
static member SendMailHtml : 
        smtpClient : SmtpClient * 
        credential : NetworkCredential * 
        subject : string * 
        body : string * 
        addresses : string[] * 
        attachments : Attachment[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailHtml(System.Net.Mail.SmtpClient,System.Net.NetworkCredential,System.String,System.String,System.String[],System.Net.Mail.Attachment[])"\]</dd><dt>credential</dt><dd>Type: System.Net.NetworkCredential<br />The credential containing the username and password for the mail account.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.String[]<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Net.Mail.Attachment[]<br />The file(s) to attach in this e-mail.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim credential As New NetworkCredential("Username@Hotmail.com", "Password")
SendMailHtml(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, credential, "Email Subject", "Message Body", {"address1@domain.com", "address2@domain.com"}, New Attachment("C:\File.txt"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailHtml">SendMailHtml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />