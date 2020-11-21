# MailUtil.MailTo Method (MailAddressCollection, String, String)
 

Runs the default mail client to send an email with the specified parameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void MailTo(
	MailAddressCollection addresses,
	string subject,
	string body
)
```

**VB**<br />
``` VB
Public Shared Sub MailTo ( 
	addresses As MailAddressCollection,
	subject As String,
	body As String
)
```

**VB Usage**<br />
``` VB Usage
Dim addresses As MailAddressCollection
Dim subject As String
Dim body As StringMailUtil.MailTo(addresses, subject, body)
```

**C++**<br />
``` C++
public:
static void MailTo(
	MailAddressCollection^ addresses, 
	String^ subject, 
	String^ body
)
```

**F#**<br />
``` F#
static member MailTo : 
        addresses : MailAddressCollection * 
        subject : string * 
        body : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>addresses</dt><dd>Type: System.Net.Mail.MailAddressCollection<br />The mail addresses.</dd><dt>subject</dt><dd>Type: System.String<br />The subject of the email.</dd><dt>body</dt><dd>Type: System.String<br />The body content of the email.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim addressCollection As New MailAddressCollection 
addressCollection.Add(New MailAddress("Address@Server.com"))
addressCollection.Add(New MailAddress("Address2@Server.com"))
MailTo(mailAddresses:=addressCollection,
       subject:="A gift for you!",
       body:="Hello World!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_MailUtil">MailUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_MailUtil_MailTo">MailTo Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />