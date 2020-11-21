# GmailClient.SendMessageHtml Method (String, String, MailAddress, ICollection(Attachment))
 

Sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SendMessageHtml(
	string subject,
	string body,
	MailAddress address,
	ICollection<Attachment> attachments
)
```

**VB**<br />
``` VB
Public Function SendMessageHtml ( 
	subject As String,
	body As String,
	address As MailAddress,
	attachments As ICollection(Of Attachment)
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim address As MailAddress
Dim attachments As ICollection(Of Attachment)
Dim returnValue As String

returnValue = instance.SendMessageHtml(subject, 
	body, address, attachments)
```

**C++**<br />
``` C++
public:
String^ SendMessageHtml(
	String^ subject, 
	String^ body, 
	MailAddress^ address, 
	ICollection<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
member SendMessageHtml : 
        subject : string * 
        body : string * 
        address : MailAddress * 
        attachments : ICollection<Attachment> -> string 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.Net.Mail.MailAddress<br />The target address that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtml(System.String,System.String,System.Net.Mail.MailAddress,System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}
SendMessageHtml("Email Subject", "Message Body", New MailAddress("address@domain.com"), attachments)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml">SendMessageHtml Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />