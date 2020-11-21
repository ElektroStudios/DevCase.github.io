# MailUtil.SendMailHtml Method (SmtpClient, String, String, String, String, MailAddressCollection, ICollection(Attachment))
 

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
	MailAddressCollection addresses,
	ICollection<Attachment> attachments
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
	addresses As MailAddressCollection,
	attachments As ICollection(Of Attachment)
)
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim username As String
Dim password As String
Dim subject As String
Dim body As String
Dim addresses As MailAddressCollection
Dim attachments As ICollection(Of Attachment)

MailUtil.SendMailHtml(smtpClient, username, 
	password, subject, body, addresses, 
	attachments)
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
	MailAddressCollection^ addresses, 
	ICollection<Attachment^>^ attachments
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
        addresses : MailAddressCollection * 
        attachments : ICollection<Attachment> -> unit 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailHtml(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.Net.Mail.MailAddressCollection,System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]</dd><dt>username</dt><dd>Type: System.String<br />The mail account username.</dd><dt>password</dt><dd>Type: System.String<br />The mail account password.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.Net.Mail.MailAddressCollection<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim addressCollection As New MailAddressCollection 
addressCollection.Add(New MailAddress("address1@domain.com"))
addressCollection.Add(New MailAddress("address2@domain.com"))

Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}

SendMailHtml(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, "Username@Hotmail.com", "Password", "Email Subject", "Message Body", addressCollection, attachments)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailHtml">SendMailHtml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />