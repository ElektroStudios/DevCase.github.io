# MailUtil.SendMailTextAsync Method (SmtpClient, NetworkCredential, String, String, String, ICollection(Attachment))
 

Asynchronously sends a mail with a plain text body through the specified SMTP server.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task SendMailTextAsync(
	SmtpClient smtpClient,
	NetworkCredential credential,
	string subject,
	string body,
	string address,
	ICollection<Attachment> attachments
)
```

**VB**<br />
``` VB
Public Shared Function SendMailTextAsync ( 
	smtpClient As SmtpClient,
	credential As NetworkCredential,
	subject As String,
	body As String,
	address As String,
	attachments As ICollection(Of Attachment)
) As Task
```

**VB Usage**<br />
``` VB Usage
Dim smtpClient As SmtpClient
Dim credential As NetworkCredential
Dim subject As String
Dim body As String
Dim address As String
Dim attachments As ICollection(Of Attachment)
Dim returnValue As Task

returnValue = MailUtil.SendMailTextAsync(smtpClient, 
	credential, subject, body, address, 
	attachments)
```

**C++**<br />
``` C++
public:
static Task^ SendMailTextAsync(
	SmtpClient^ smtpClient, 
	NetworkCredential^ credential, 
	String^ subject, 
	String^ body, 
	String^ address, 
	ICollection<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
static member SendMailTextAsync : 
        smtpClient : SmtpClient * 
        credential : NetworkCredential * 
        subject : string * 
        body : string * 
        address : string * 
        attachments : ICollection<Attachment> -> Task 

```


#### Parameters
&nbsp;<dl><dt>smtpClient</dt><dd>Type: System.Net.Mail.SmtpClient<br />\[Missing <param name="smtpClient"/> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailTextAsync(System.Net.Mail.SmtpClient,System.Net.NetworkCredential,System.String,System.String,System.String,System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]</dd><dt>credential</dt><dd>Type: System.Net.NetworkCredential<br />The credential containing the username and password for the mail account.</dd><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.String<br />The target address that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd></dl>

#### Return Value
Type: Task<br />\[Missing <returns> documentation for "M:DevCase.Core.NET.Tools.MailUtil.SendMailTextAsync(System.Net.Mail.SmtpClient,System.Net.NetworkCredential,System.String,System.String,System.String,System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim credential As New NetworkCredential("Username@Hotmail.com", "Password")
Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}
Await SendMailTextAsync(DevCase.Core.NET.SmtpClients.MicrosoftLiveSmtpClient, credential, "Email Subject", "Message Body", "address@domain.com", attachments)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_SendMailTextAsync">SendMailTextAsync Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />