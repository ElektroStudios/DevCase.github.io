# GmailClient.SendMessageHtmlAsync Method (String, String, MailAddressCollection, Attachment[])
 

Asynchronously sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> SendMessageHtmlAsync(
	string subject,
	string body,
	MailAddressCollection addresses,
	params Attachment[] attachments
)
```

**VB**<br />
``` VB
Public Function SendMessageHtmlAsync ( 
	subject As String,
	body As String,
	addresses As MailAddressCollection,
	ParamArray attachments As Attachment()
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim addresses As MailAddressCollection
Dim attachments As Attachment()
Dim returnValue As Task(Of String)

returnValue = instance.SendMessageHtmlAsync(subject, 
	body, addresses, attachments)
```

**C++**<br />
``` C++
public:
Task<String^>^ SendMessageHtmlAsync(
	String^ subject, 
	String^ body, 
	MailAddressCollection^ addresses, 
	... array<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
member SendMessageHtmlAsync : 
        subject : string * 
        body : string * 
        addresses : MailAddressCollection * 
        attachments : Attachment[] -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.Net.Mail.MailAddressCollection<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Net.Mail.Attachment[]<br />The file(s) to attach in this e-mail.</dd></dl>

#### Return Value
Type: Task(String)<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtmlAsync(System.String,System.String,System.Net.Mail.MailAddressCollection,System.Net.Mail.Attachment[])"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim addressCollection As New MailAddressCollection 
addressCollection.Add(New MailAddress("address1@domain.com"))
addressCollection.Add(New MailAddress("address2@domain.com"))
Await SendMessageHtmlAsync("Email Subject", "Message Body", addressCollection, New Attachment("C:\File.txt"))
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync">SendMessageHtmlAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />