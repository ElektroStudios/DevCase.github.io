# GmailClient.SendMessageHtmlAsync Method (String, String, String[])
 

Asynchronously sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> SendMessageHtmlAsync(
	string subject,
	string body,
	string[] addresses
)
```

**VB**<br />
``` VB
Public Function SendMessageHtmlAsync ( 
	subject As String,
	body As String,
	addresses As String()
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim addresses As String()
Dim returnValue As Task(Of String)

returnValue = instance.SendMessageHtmlAsync(subject, 
	body, addresses)
```

**C++**<br />
``` C++
public:
Task<String^>^ SendMessageHtmlAsync(
	String^ subject, 
	String^ body, 
	array<String^>^ addresses
)
```

**F#**<br />
``` F#
member SendMessageHtmlAsync : 
        subject : string * 
        body : string * 
        addresses : string[] -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>addresses</dt><dd>Type: System.String[]<br />The target addresses that will receive our sent mail.</dd></dl>

#### Return Value
Type: Task(String)<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtmlAsync(System.String,System.String,System.String[])"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Await SendMessageHtmlAsync("Email Subject", "Message Body", {"address1@domain.com", "address2@domain.com"})
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync">SendMessageHtmlAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />