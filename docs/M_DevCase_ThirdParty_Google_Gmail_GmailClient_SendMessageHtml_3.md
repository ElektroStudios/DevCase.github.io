# GmailClient.SendMessageHtml Method (String, String, MailAddressCollection)
 

Sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SendMessageHtml(
	string subject,
	string body,
	MailAddressCollection addresses
)
```

**VB**<br />
``` VB
Public Function SendMessageHtml ( 
	subject As String,
	body As String,
	addresses As MailAddressCollection
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim addresses As MailAddressCollection
Dim returnValue As String

returnValue = instance.SendMessageHtml(subject, 
	body, addresses)
```

**C++**<br />
``` C++
public:
String^ SendMessageHtml(
	String^ subject, 
	String^ body, 
	MailAddressCollection^ addresses
)
```

**F#**<br />
``` F#
member SendMessageHtml : 
        subject : string * 
        body : string * 
        addresses : MailAddressCollection -> string 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.Net.Mail.MailAddressCollection<br />The target addresses that will receive our sent mail.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtml(System.String,System.String,System.Net.Mail.MailAddressCollection)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim addressCollection As New MailAddressCollection 
addressCollection.Add(New MailAddress("address1@domain.com"))
addressCollection.Add(New MailAddress("address2@domain.com"))
SendMessageHtml("Email Subject", "Message Body", addressCollection)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml">SendMessageHtml Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />