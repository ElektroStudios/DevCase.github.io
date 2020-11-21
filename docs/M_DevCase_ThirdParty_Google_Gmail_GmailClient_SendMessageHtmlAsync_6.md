# GmailClient.SendMessageHtmlAsync Method (String, String, String)
 

Asynchronously sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> SendMessageHtmlAsync(
	string subject,
	string body,
	string address
)
```

**VB**<br />
``` VB
Public Function SendMessageHtmlAsync ( 
	subject As String,
	body As String,
	address As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim address As String
Dim returnValue As Task(Of String)

returnValue = instance.SendMessageHtmlAsync(subject, 
	body, address)
```

**C++**<br />
``` C++
public:
Task<String^>^ SendMessageHtmlAsync(
	String^ subject, 
	String^ body, 
	String^ address
)
```

**F#**<br />
``` F#
member SendMessageHtmlAsync : 
        subject : string * 
        body : string * 
        address : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.String<br />The target address that will receive our sent mail.</dd></dl>

#### Return Value
Type: Task(String)<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtmlAsync(System.String,System.String,System.String)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Await SendMessageHtmlAsync("Email Subject", "Message Body", "address@domain.com")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtmlAsync">SendMessageHtmlAsync Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />