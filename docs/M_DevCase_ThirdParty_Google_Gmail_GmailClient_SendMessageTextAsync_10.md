# GmailClient.SendMessageTextAsync Method (String, String, String[], ICollection(Attachment))
 

Asynchronously sends a mail with a plain text body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> SendMessageTextAsync(
	string subject,
	string body,
	string[] addresses,
	ICollection<Attachment> attachments
)
```

**VB**<br />
``` VB
Public Function SendMessageTextAsync ( 
	subject As String,
	body As String,
	addresses As String(),
	attachments As ICollection(Of Attachment)
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim addresses As String()
Dim attachments As ICollection(Of Attachment)
Dim returnValue As Task(Of String)

returnValue = instance.SendMessageTextAsync(subject, 
	body, addresses, attachments)
```

**C++**<br />
``` C++
public:
Task<String^>^ SendMessageTextAsync(
	String^ subject, 
	String^ body, 
	array<String^>^ addresses, 
	ICollection<Attachment^>^ attachments
)
```

**F#**<br />
``` F#
member SendMessageTextAsync : 
        subject : string * 
        body : string * 
        addresses : string[] * 
        attachments : ICollection<Attachment> -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.String[]<br />The target addresses that will receive our sent mail.</dd><dt>attachments</dt><dd>Type: System.Collections.Generic.ICollection(Attachment)<br />The file(s) to attach in this e-mail.</dd></dl>

#### Return Value
Type: Task(String)<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageTextAsync(System.String,System.String,System.String[],System.Collections.Generic.ICollection{System.Net.Mail.Attachment})"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim attachments As New Collection(Of Attachment) From {New Attachment("C:\File1.txt"), New Attachment("C:\File2.txt")}
Await SendMessageTextAsync("Email Subject", "Message Body", {"address1@domain.com", "address2@domain.com"}, attachments)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageTextAsync">SendMessageTextAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />