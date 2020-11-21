# MailUtil.SendMailAsync Method 
 

Asynchronously sends a mail through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task SendMailAsync(
	SmtpClient smtpClient,
	string username,
	string password,
	string subject,
	string body,
	MailAddressCollection addresses,
	ICollection<Attachment> attachments,
	bool isBodyHtml
)
```

**VB**<br />
``` VB
Public Shared Function SendMailAsync ( 
	smtpClient As SmtpClient,
	username As String,
	password As String,
	subject As String,
	body As String,
	addresses As MailAddressCollection,
	attachments As ICollection(Of Attachment),
	isBodyHtml As Boolean
) As Task
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
Dim isBodyHtml As Boolean
Dim returnValue As Task

returnValue = MailUtil.SendMailAsync(smtpClient, 
	username, password, subject, body, 
	addresses, attachments, isBodyHtml)
```

**C++**<br />
``` C++
public:
static Task^ SendMailAsync(
	SmtpClient^ smtpClient, 
	String^ username, 
	String^ password, 
	String^ subject, 
	String^ body, 
	MailAddressCollection^ addresses, 
	ICollection<Attachment^>^ attachments, 
	bool isBodyHtml
)
```

**F#**<br />
``` F#
static member SendMailAsync : 
        smtpClient : SmtpClient * 
        username : string * 
        password : string * 
        subject : string * 
        body : string * 
        addresses : MailAddressCollection * 
        attachments : ICollection<Attachment> * 
        isBodyHtml : bool -> Task 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailAsync(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.Net.Mail.MailAddressCollection,System.Collections.Generic.ICollection{System.Net.Mail.Attachment},System.Boolean)"\]</dd><dt>username</dt><dd>Type: System.String<br />The mail account username.</dd><dt>password</dt><dd>Type: System.String<br />The mail account password.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.Net.Mail.MailAddressCollection<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd><dt>isBodyHtml</dt><dd>Type: System.Boolean<br />Indicates whether the mail body is html or plain text.</dd></dl>

#### Return Value
Type: Task<br />\[Missing <returns> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailAsync(System.Net.Mail.SmtpClient,System.String,System.String,System.String,System.String,System.Net.Mail.MailAddressCollection,System.Collections.Generic.ICollection{System.Net.Mail.Attachment},System.Boolean)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim addressCollection As New MailAddressCollection 
addressCollection.Add(New MailAddress("address1@domain.com"))
addressCollection.Add(New MailAddress("address2@domain.com"))

Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}

Await SendMailAsync("Username@Hotmail.com", "Password", "Email Subject", "Message Body", addressCollection, attachments, isBodyHtml:=False)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />