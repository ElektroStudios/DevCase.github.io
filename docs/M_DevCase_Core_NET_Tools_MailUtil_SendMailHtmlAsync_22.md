# MailUtil.SendMailHtmlAsync Method (SmtpClient, String, String, String, String, String[], ICollection(Attachment))
 

Asynchronously sends a mail with a HTML body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task SendMailHtmlAsync(
	SmtpClient smtpClient,
	string username,
	string password,
	string subject,
	string body,
	string[] addresses,
	ICollection<Attachment> attachments
)
```

**VB**<br />
``` VB
Public Shared Function SendMailHtmlAsync ( 
	smtpClient As SmtpClient,
	username As String,
	password As String,
	subject As String,
	body As String,
	addresses As String(),
	attachments As ICollection(Of Attachment)
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim username As String
Dim password As String
Dim subject As String
Dim body As String
Dim addresses As String()
Dim attachments As ICollection(Of Attachment)
Dim returnValue As Task

returnValue = MailUtil.SendMailHtmlAsync(smtpClient, 
	username, password, subject, body, 
	addresses, attachments)
```

**C++**<br />
``` C++
public:
static Task^ SendMailHtmlAsync(
	SmtpClient^ smtpClient, 
	String^ username, 
	String^ password, 
	String^ subject, 
	String^ body, 
	array<String^>^ addresses, 
	ICollection<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
static member SendMailHtmlAsync : 
        smtpClient : SmtpClient * 
        username : string * 
        password : string * 
        subject : string * 
        body : string * 
        addresses : string[] * 
        attachments : ICollection<Attachment> -> Task 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailHtmlAsync(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.String[],System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]</dd><dt>username</dt><dd>Type: System.String<br />The mail account username.</dd><dt>password</dt><dd>Type: System.String<br />The mail account password.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.String[]<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd></dl>

#### Return Value
Type: Task<br />\[Missing <returns> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailHtmlAsync(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.String[],System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}
Await SendMailHtmlAsync(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, "Username@Hotmail.com", "Password", "Email Subject", "Message Body", {"address1@domain.com", "address2@domain.com"}, attachments)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailHtmlAsync">SendMailHtmlAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />