# GmailClient.SendMessageHtml Method (String, String, String)
 

Sends a mail with a HTML body.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SendMessageHtml(
	string subject,
	string body,
	string address
)
```

**VB**<br />
``` VB
Public Function SendMessageHtml ( 
	subject As String,
	body As String,
	address As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim subject As String
Dim body As String
Dim address As String
Dim returnValue As String

returnValue = instance.SendMessageHtml(subject, 
	body, address)
```

**C++**<br />
``` C++
public:
String^ SendMessageHtml(
	String^ subject, 
	String^ body, 
	String^ address
)
```

**F#**<br />
``` F#
member SendMessageHtml : 
        subject : string * 
        body : string * 
        address : string -> string 

```


#### Parameters
&nbsp;<dl><dt>subject</dt><dd>Type: System.String<br />The mail subject.</dd><dt>body</dt><dd>Type: System.String<br />The mail body.</dd><dt>address</dt><dd>Type: System.String<br />The target address that will receive our sent mail.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.SendMessageHtml(System.String,System.String,System.String)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
SendMessageHtml("Email Subject", "Message Body", "address@domain.com")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Gmail_GmailClient_SendMessageHtml">SendMessageHtml Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />